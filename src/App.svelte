<script>
	import SpeechRecognition from './components/SpeechRecognition.svelte';
	import GoogleKeep from './components/GoogleKeep.svelte';
	import Github from './components/GitHub.svelte';
	import StackOverflow from './components/StackOverflow.svelte';
	import Linkedin from './components/Linkedin.svelte';
	import Twitter from './components/Twitter.svelte';
	import Medium from './components/Medium.svelte';
	import YouTube from './components/YouTube.svelte';
	import GoogleCalendar from './components/GoogleCalendar.svelte';
	import GoogleGmail from './components/GoogleGmail.svelte';
	import GoogleDrive from './components/GoogleDrive.svelte';
	import GoogleMaps from './components/GoogleMaps.svelte';
	import GitEe from './components/GitEe.svelte';
	import NpmJs from './components/NpmJs.svelte';
	import PyPi from './components/PyPi.svelte';
	import Bing from './components/Bing.svelte';
	import Quora from './components/Quora.svelte';
	import DevTo from './components/DevTo.svelte';
	import SearchCode from './components/SearchCode.svelte';
	import Kaggle from './components/Kaggle.svelte';
	import GoogleDataset from './components/GoogleDataset.svelte';
	import DataGov from './components/DataGov.svelte';
	import GoogleScholar from './components/GoogleScholar.svelte';
	import BaseSearch from './components/BaseSearch.svelte';
	import CoreSearch from './components/CoreSearch.svelte';
	import SemanticScholar from './components/SemanticScholar.svelte';
	import BaiduScholar from './components/BaiduScholar.svelte';


	let cardSettigns = {
		classContainer : 'flex flex-col flex-column md:flex-row md:max-w-sm rounded-lg bg-gray-100 shadow-md',
		classImg : 'w-full h-14 w-14 md:h-14 object-contain md:w-14 ml-2 mb-3 ',
		classInput : 'form-control relative flex-auto min-w-0 block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:border-blue-600 hover:border-blue-600 focus:outline-none',
		classButton : 'btn inline-block px-6 py-2.5 bg-gray-400 text-white font-medium text-xs leading-tight uppercase rounded shadow-md hover:bg-gray-500 hover:shadow-lg focus:shadow-lg focus:outline-none focus:ring-0  active:shadow-lg transition duration-150 ease-in-out flex items-center'
	}
</script>

<SpeechRecognition />

	<center>
<h2>Welcome to the DullUser.Com One Page Search Tool. Bookmark this page :-)</h2>
<p>A very handy online searching tool where you can visit and search your favorite daily use websites in one click. You don't need to open website in another browser tab, search and type for text.</p>
	</center>


<div class="text-3xl leading-tight text-center bg-gray-300 text-gray-700">
	<span class="text-xl inline-block py-2 px-10 leading-none text-center whitespace-nowrap align-baseline font-bold bg-slate-600 text-white rounded-full mb-3 mt-3">Developer Search</span>
</div>

<div class="grid gap-4 grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 mt-5 ml-5">
	<Github {cardSettigns}/>
	<StackOverflow {cardSettigns}/>
	<Twitter {cardSettigns}/>
	<Linkedin {cardSettigns}/>
	<Medium {cardSettigns}/>
	<GitEe {cardSettigns}/>
	<NpmJs {cardSettigns}/>
	<PyPi {cardSettigns}/>
	<DevTo {cardSettigns}/>
	<SearchCode {cardSettigns}/>
</div>

<div class="text-3xl leading-tight text-center bg-gray-300 text-gray-700 mt-5 mb-5">
	<span class="text-xl inline-block py-2 px-10 leading-none text-center whitespace-nowrap align-baseline font-bold bg-slate-600 text-white rounded-full mb-3 mt-3">General Search</span>
</div>

<div class="grid gap-4 grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 mt-5 ml-5">
	<YouTube {cardSettigns}/>
	<GoogleKeep {cardSettigns}/>
	<GoogleGmail {cardSettigns}/>
	<GoogleCalendar {cardSettigns}/>
	<GoogleDrive {cardSettigns}/>
	<GoogleMaps {cardSettigns}/>
	<Bing {cardSettigns}/>
	<Quora {cardSettigns}/>
</div>

<div class="text-3xl leading-tight text-center bg-gray-300 text-gray-700 mt-5 mb-5">
	<span class="text-xl inline-block py-2 px-10 leading-none text-center whitespace-nowrap align-baseline font-bold bg-slate-600 text-white rounded-full mb-3 mt-3">Data Science Search</span>
</div>

<div class="grid gap-4 grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 mt-5 ml-5">
	<Kaggle {cardSettigns}/>
	<GoogleDataset {cardSettigns}/>
	<DataGov {cardSettigns}/>
</div>

<div class="text-3xl leading-tight text-center bg-gray-300 text-gray-700">
	<span class="text-xl inline-block py-2 px-10 leading-none text-center whitespace-nowrap align-baseline font-bold bg-slate-600 text-white rounded-full mb-3 mt-3">Scientific Search</span>
</div>

<div class="grid gap-4 grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 mt-5 ml-5">
	<GoogleScholar {cardSettigns}/>
	<BaseSearch {cardSettigns}/>
	<CoreSearch {cardSettigns}/>
	<SemanticScholar {cardSettigns}/>
	<BaiduScholar {cardSettigns}/>
</div>

<p></p><br>
	<center>
<h2>Copyright ©2022 DullUser.Com | info@dulluser.com | Concept by Padmaraj & Rahul | Privacy Policy | Terms of Use | Manage Preferences | Sitemap | About</h2>
<p>In 1 month time we saved 20000 Work hours serving 10000 online users.</p>
<a href="https://twitter.com/UserDull?ref_src=twsrc%5Etfw" class="twitter-follow-button" data-show-count="false">Follow @UserDull</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
	</center>

<style lang="postcss" global>
	@tailwind base;
	@tailwind components;
	@tailwind utilities;
</style>
