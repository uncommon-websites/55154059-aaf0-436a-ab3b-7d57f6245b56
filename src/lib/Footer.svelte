<script lang="ts">
	import { Twitter, Linkedin, Github, Youtube } from 'lucide-svelte';
</script>

<footer class="bg-black text-white pt-20 pb-10 px-6">
	<div class="max-w-[1200px] mx-auto">
		<div class="grid grid-cols-2 md:grid-cols-6 gap-10 mb-20">
			<!-- Logo Column -->
			<div class="col-span-2">
				<a href="/" class="flex items-center gap-2 text-white mb-6">
					<div class="w-8 h-8 bg-white rounded-lg flex items-center justify-center">
						<span class="text-black font-bold text-xl">H</span>
					</div>
					<span class="font-bold text-xl tracking-tight">HiPeople</span>
				</a>
				<p class="text-gray-400 text-sm max-w-xs">
					The unified Talent Intelligence Layer for modern hiring teams.
				</p>
			</div>

			<!-- Columns -->
			<div>
				<h4 class="text-sm font-medium text-gray-400 mb-4">Product</h4>
				<ul class="space-y-3 text-sm text-gray-300">
					<li><a href="#" class="hover:text-white">AI Screening</a></li>
					<li><a href="#" class="hover:text-white">Assessments</a></li>
					<li><a href="#" class="hover:text-white">Reference Checks</a></li>
					<li><a href="#" class="hover:text-white">Integrations</a></li>
					<li><a href="#" class="hover:text-white">Security</a></li>
				</ul>
				
				<h4 class="text-sm font-medium text-gray-400 mt-8 mb-4">Company</h4>
				<ul class="space-y-3 text-sm text-gray-300">
					<li><a href="#" class="hover:text-white">About Us</a></li>
					<li><a href="#" class="hover:text-white">Customers</a></li>
					<li><a href="#" class="hover:text-white">Careers</a></li>
					<li><a href="#" class="hover:text-white">Blog</a></li>
				</ul>
			</div>

			<div>
				<h4 class="text-sm font-medium text-gray-400 mb-4">Integrations</h4>
				<ul class="space-y-3 text-sm text-gray-300">
					<li><a href="#" class="hover:text-white">Greenhouse</a></li>
					<li><a href="#" class="hover:text-white">Lever</a></li>
					<li><a href="#" class="hover:text-white">Workday</a></li>
					<li><a href="#" class="hover:text-white">Ashby</a></li>
					<li><a href="#" class="hover:text-white">SmartRecruiters</a></li>
				</ul>
			</div>

			<div>
				<h4 class="text-sm font-medium text-gray-400 mb-4">Resources</h4>
				<ul class="space-y-3 text-sm text-gray-300">
					<li><a href="#" class="hover:text-white">Glossary</a></li>
					<li><a href="#" class="hover:text-white">Interview Library</a></li>
					<li><a href="#" class="hover:text-white">Skills Hiring Guide</a></li>
					<li><a href="#" class="hover:text-white">Job Descriptions</a></li>
					<li><a href="#" class="hover:text-white">Talent Report 2025</a></li>
				</ul>
			</div>

			<div>
				<h4 class="text-sm font-medium text-gray-400 mb-4">Support</h4>
				<ul class="space-y-3 text-sm text-gray-300">
					<li><a href="#" class="hover:text-white">Help Center</a></li>
					<li><a href="#" class="hover:text-white">API Docs</a></li>
					<li><a href="#" class="hover:text-white">System Status</a></li>
				</ul>
			</div>
		</div>

		<div class="border-t border-gray-800 pt-8 flex flex-col md:flex-row items-center justify-between gap-4">
			<div class="flex items-center gap-6">
				<a href="#" class="text-gray-500 hover:text-white transition-colors"><Linkedin size={20} /></a>
				<a href="#" class="text-gray-500 hover:text-white transition-colors"><Twitter size={20} /></a>
			</div>
			
			<div class="flex items-center gap-6 text-xs text-gray-500">
				<span>© 2025 HiPeople. All rights reserved.</span>
				<a href="#" class="hover:text-gray-300">Terms & Conditions</a>
				<a href="#" class="hover:text-gray-300">Privacy Policy</a>
				<a href="#" class="hover:text-gray-300">GDPR</a>
			</div>
		</div>
	</div>
</footer>
