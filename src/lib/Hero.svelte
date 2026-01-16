<script lang="ts">
	import { ArrowRight, ChevronDown, Search, Bell, CheckSquare, Phone, BarChart2, Zap, Layout, Users, Briefcase, Building2, Plus, MoreHorizontal, Filter, RefreshCw, Download, ShieldCheck, Globe } from 'lucide-svelte';
</script>

<section class="pt-40 pb-20 px-6 text-center max-w-[1400px] mx-auto">
	<a href="#" class="inline-flex items-center gap-2 text-xs font-medium text-gray-500 hover:text-black mb-8 border border-gray-200 rounded-full px-3 py-1 bg-white hover:border-gray-300 transition-colors">
		G2 Leader Winter 2025: Best Usability & Results
		<ArrowRight size={12} />
	</a>

	<h1 class="text-[56px] leading-[1.1] font-serif tracking-tight text-gray-900 mb-6 max-w-4xl mx-auto">
		The Talent Intelligence Layer<br/>for your ATS.
	</h1>

	<p class="text-lg text-gray-500 mb-10 max-w-xl mx-auto text-balance">
		HiPeople accelerates hiring decisions with AI-powered screening, assessments, and reference checks—all in one unified platform.
	</p>

	<div class="flex items-center justify-center gap-4 mb-20">
		<a href="#" class="bg-black text-white text-sm font-medium px-5 py-2.5 rounded-lg hover:bg-gray-800 transition-colors">
			Book a demo
		</a>
		<a href="#" class="text-sm font-medium text-gray-600 hover:text-black border border-gray-200 px-5 py-2.5 rounded-lg hover:border-gray-300 transition-colors">
			Watch product tour
		</a>
	</div>

	<!-- Dashboard Preview -->
	<div class="relative rounded-xl overflow-hidden shadow-2xl border border-gray-200 bg-white text-left mx-auto max-w-[1200px]">
		<!-- Tabs -->
		<div class="flex border-b border-gray-200 bg-gray-50/50">
			<button class="px-8 py-3 text-xs font-medium text-gray-500 hover:text-black border-b-2 border-transparent">AI Screening</button>
			<button class="px-8 py-3 text-xs font-medium text-gray-500 hover:text-black border-b-2 border-transparent">Assessments</button>
			<button class="px-8 py-3 text-xs font-medium text-black border-b-2 border-black bg-white">Talent Intelligence</button>
			<button class="px-8 py-3 text-xs font-medium text-gray-500 hover:text-black border-b-2 border-transparent">Reference Checks</button>
		</div>

		<!-- UI Container -->
		<div class="flex h-[600px] bg-white">
			<!-- Sidebar -->
			<div class="w-[240px] border-r border-gray-200 flex flex-col text-[13px] text-gray-600">
				<div class="p-3 flex items-center gap-2 font-medium text-black border-b border-gray-100">
					<div class="w-5 h-5 bg-black rounded flex items-center justify-center text-white text-[10px]">H</div>
					HiPeople
					<ChevronDown size={14} class="ml-auto opacity-50" />
				</div>
				
				<div class="p-2 space-y-0.5">
					<div class="flex items-center gap-2 px-2 py-1.5 hover:bg-gray-50 rounded cursor-pointer">
						<Search size={14} /> Global Search
					</div>
					<div class="flex items-center gap-2 px-2 py-1.5 hover:bg-gray-50 rounded cursor-pointer">
						<Bell size={14} /> Alerts
					</div>
					<div class="flex items-center gap-2 px-2 py-1.5 hover:bg-gray-50 rounded cursor-pointer">
						<Phone size={14} /> AI Screening
					</div>
					<div class="flex items-center gap-2 px-2 py-1.5 hover:bg-gray-50 rounded cursor-pointer">
						<CheckSquare size={14} /> Assessments
					</div>
					<div class="flex items-center gap-2 px-2 py-1.5 bg-gray-100 text-black font-medium rounded cursor-pointer">
						<BarChart2 size={14} /> Intelligence
					</div>
					<div class="flex items-center gap-2 px-2 py-1.5 hover:bg-gray-50 rounded cursor-pointer">
						<Users size={14} /> References
					</div>
				</div>

				<div class="mt-2 px-4 text-[11px] font-medium text-gray-400">Integrations</div>
				<div class="p-2 space-y-0.5">
					<div class="flex items-center gap-2 px-2 py-1.5 hover:bg-gray-50 rounded cursor-pointer">
						<div class="w-4 h-4 bg-green-500 rounded-sm"></div> Greenhouse
					</div>
					<div class="flex items-center gap-2 px-2 py-1.5 hover:bg-gray-50 rounded cursor-pointer">
						<div class="w-4 h-4 bg-blue-500 rounded-sm"></div> Lever
					</div>
					<div class="flex items-center gap-2 px-2 py-1.5 hover:bg-gray-50 rounded cursor-pointer">
						<div class="w-4 h-4 bg-orange-500 rounded-sm"></div> Workday
					</div>
				</div>
			</div>

			<!-- Main Content -->
			<div class="flex-1 flex flex-col bg-gray-50/30">
				<!-- Header -->
				<div class="h-14 border-b border-gray-200 flex items-center justify-between px-6 bg-white">
					<div class="flex items-center gap-2 text-sm text-gray-500">
						<BarChart2 size={16} />
						<span>Intelligence</span>
						<span class="text-gray-300">/</span>
						<span class="text-black font-medium">Hiring Quality Dashboard</span>
					</div>
					<div class="flex items-center gap-3">
						<div class="flex -space-x-2">
							<div class="w-6 h-6 rounded-full bg-blue-100 border-2 border-white flex items-center justify-center text-[10px]">SJ</div>
							<div class="w-6 h-6 rounded-full bg-green-100 border-2 border-white flex items-center justify-center text-[10px]">JK</div>
						</div>
						<button class="text-xs font-medium text-gray-600 hover:text-black flex items-center gap-1">
							Export
						</button>
					</div>
				</div>

				<!-- Dashboard Content -->
				<div class="p-6 overflow-hidden">
					<div class="mb-6 flex items-center justify-between">
						<div>
							<h2 class="text-lg font-semibold text-gray-900">Hiring Quality Insights</h2>
							<p class="text-sm text-gray-500">Real-time data on candidate performance and screening efficiency.</p>
						</div>
						<div class="flex items-center gap-2">
							<button class="text-xs font-medium text-gray-500 hover:text-black flex items-center gap-1 px-2 py-1">
								<RefreshCw size={12} /> Sync ATS
							</button>
							<button class="bg-black text-white text-xs font-medium px-3 py-1.5 rounded-md hover:bg-gray-800 flex items-center gap-1">
								<Plus size={12} /> New Assessment
							</button>
						</div>
					</div>

					<div class="grid grid-cols-5 gap-6 h-full">
						<!-- Chart 1: Quality of Hire -->
						<div class="col-span-3 bg-white rounded-lg border border-gray-200 p-4 shadow-sm">
							<div class="flex items-center justify-between mb-4">
								<h3 class="text-sm font-medium text-gray-900">Candidate Quality Score by Source</h3>
								<MoreHorizontal size={14} class="text-gray-400" />
							</div>
							<div class="flex items-center gap-4 text-[10px] text-gray-500 mb-4">
								<div class="flex items-center gap-1"><div class="w-2 h-2 rounded-full bg-blue-200"></div> LinkedIn</div>
								<div class="flex items-center gap-1"><div class="w-2 h-2 rounded-full bg-blue-300"></div> Referrals</div>
								<div class="flex items-center gap-1"><div class="w-2 h-2 rounded-full bg-blue-400"></div> Inbound</div>
								<div class="flex items-center gap-1"><div class="w-2 h-2 rounded-full bg-blue-500"></div> Agency</div>
							</div>
							
							<div class="relative h-[250px] w-full mt-8">
								<div class="absolute left-0 top-0 bottom-0 w-8 flex flex-col justify-between text-[10px] text-gray-400 text-right pr-2">
									<span>100%</span>
									<span>80%</span>
									<span>60%</span>
									<span>40%</span>
									<span>20%</span>
									<span>0%</span>
								</div>
								<div class="ml-10 h-full flex items-end justify-between px-4 border-l border-b border-gray-100">
									<div class="w-8 flex flex-col gap-0.5 items-center relative">
										<div class="w-full bg-blue-200 h-16 rounded-t-sm"></div>
										<div class="w-full bg-blue-300 h-24"></div>
										<div class="absolute -bottom-6 text-[10px] text-gray-500">Q1</div>
									</div>
									<div class="w-8 flex flex-col gap-0.5 items-center relative">
										<div class="w-full bg-blue-300 h-20 rounded-t-sm"></div>
										<div class="w-full bg-blue-400 h-32"></div>
										<div class="absolute -bottom-6 text-[10px] text-gray-500">Q2</div>
										<div class="absolute bottom-full mb-2 left-1/2 -translate-x-1/2 bg-gray-900 text-white text-[10px] px-2 py-1 rounded whitespace-nowrap z-10">
											Quality Index <span class="text-green-400 ml-1">+12%</span>
										</div>
									</div>
									<div class="w-8 flex flex-col gap-0.5 items-center relative">
										<div class="w-full bg-blue-400 h-28 rounded-t-sm"></div>
										<div class="w-full bg-blue-500 h-40"></div>
										<div class="absolute -bottom-6 text-[10px] text-gray-500">Q3</div>
									</div>
								</div>
							</div>
						</div>

						<!-- Chart 2: Time Saved -->
						<div class="col-span-2 bg-white rounded-lg border border-gray-200 p-4 shadow-sm">
							<div class="flex items-center justify-between mb-4">
								<h3 class="text-sm font-medium text-gray-900">Recruiter Hours Saved</h3>
								<MoreHorizontal size={14} class="text-gray-400" />
							</div>
							<div class="flex flex-wrap gap-2 text-[10px] text-gray-500 mb-8">
								<div class="flex items-center gap-1"><div class="w-2 h-2 rounded-full bg-green-500"></div> Screening</div>
								<div class="flex items-center gap-1"><div class="w-2 h-2 rounded-full bg-blue-500"></div> Interviews</div>
								<div class="flex items-center gap-1"><div class="w-2 h-2 rounded-full bg-purple-500"></div> References</div>
							</div>

							<div class="relative w-48 h-48 mx-auto">
								<svg viewBox="0 0 100 100" class="w-full h-full transform -rotate-90">
									<circle cx="50" cy="50" r="40" fill="transparent" stroke="#f0fdf4" stroke-width="16" />
									<circle cx="50" cy="50" r="40" fill="transparent" stroke="#22c55e" stroke-width="16" stroke-dasharray="120 251" stroke-dashoffset="0" />
									<circle cx="50" cy="50" r="40" fill="transparent" stroke="#3b82f6" stroke-width="16" stroke-dasharray="80 251" stroke-dashoffset="-120" />
									<circle cx="50" cy="50" r="40" fill="transparent" stroke="#a855f7" stroke-width="16" stroke-dasharray="51 251" stroke-dashoffset="-200" />
								</svg>
								<div class="absolute inset-0 flex items-center justify-center flex-col">
									<span class="text-2xl font-bold text-gray-900">23h</span>
									<span class="text-[10px] text-gray-500">Saved / Week</span>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>

	<!-- Logos -->
	<div class="mt-20 flex flex-wrap justify-center items-center gap-12 opacity-60 grayscale">
		<span class="font-bold text-xl">Zapier</span>
		<span class="font-bold text-xl">Grammarly</span>
		<span class="font-bold text-xl">Pleo</span>
		<span class="font-bold text-xl">DAZN</span>
		<span class="font-bold text-xl">Variety</span>
		<span class="font-bold text-xl">Fujifilm</span>
	</div>
</section>
