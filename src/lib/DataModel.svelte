<script lang="ts">
	import { User, Briefcase, Building2, Plus, MoreHorizontal, CheckSquare, Phone, ShieldCheck } from 'lucide-svelte';
</script>

<section class="max-w-[1200px] mx-auto px-6 py-20">
	<div class="text-center max-w-3xl mx-auto mb-20">
		<h2 class="text-4xl font-serif text-gray-900 mb-6">
			A seismic shift in hiring flexibility. <span class="text-gray-500 font-sans text-xl font-normal block mt-4">HiPeople's unified talent intelligence layer adapts to how your team hires, not the other way around. Your hiring flow — perfectly reflected in your intelligence.</span>
		</h2>
		<button class="mt-8 px-4 py-2 bg-white border border-gray-200 rounded-full text-sm font-medium hover:border-gray-300 transition-colors">
			Explore our unified layer
		</button>
	</div>

	<!-- Data Model Visual -->
	<div class="relative bg-gray-50/50 rounded-xl p-10 md:p-20 border border-gray-100 overflow-hidden">
		<!-- Background Grid -->
		<div class="absolute inset-0" style="background-image: radial-gradient(#e5e7eb 1px, transparent 1px); background-size: 20px 20px; opacity: 0.5;"></div>

		<!-- Top Filters -->
		<div class="flex justify-center gap-2 mb-16 relative z-10">
			<button class="px-3 py-1 bg-white border border-gray-200 rounded-full text-xs font-medium shadow-sm">Volume Hiring</button>
			<button class="px-3 py-1 bg-white border border-gray-200 rounded-full text-xs font-medium shadow-sm">Tech Teams</button>
			<button class="px-3 py-1 bg-white border border-gray-200 rounded-full text-xs font-medium shadow-sm">Executive Search</button>
			<button class="px-3 py-1 bg-white border border-gray-200 rounded-full text-xs font-medium shadow-sm">Startups</button>
		</div>

		<!-- Objects Diagram -->
		<div class="relative max-w-4xl mx-auto h-[500px]">
			<!-- Connecting Lines (SVG) -->
			<svg class="absolute inset-0 w-full h-full pointer-events-none z-0">
				<!-- User to Person -->
				<path d="M 200 150 C 200 200, 250 250, 300 300" fill="none" stroke="#e5e7eb" stroke-width="2" stroke-dasharray="4 4" />
				<!-- Person to Deal -->
				<path d="M 450 300 C 500 250, 550 200, 600 150" fill="none" stroke="#e5e7eb" stroke-width="2" stroke-dasharray="4 4" />
				<!-- Person to Add Object -->
				<path d="M 450 350 C 500 350, 550 350, 600 350" fill="none" stroke="#e5e7eb" stroke-width="2" stroke-dasharray="4 4" />
			</svg>

			<!-- AI Screening Object -->
			<div class="absolute top-10 left-10 w-64 bg-white rounded-lg border border-gray-200 shadow-sm z-10">
				<div class="p-3 border-b border-gray-100 flex items-center justify-between bg-gray-50/50 rounded-t-lg">
					<div class="flex items-center gap-2">
						<div class="w-6 h-6 rounded bg-blue-100 flex items-center justify-center text-blue-600">
							<Phone size={14} />
						</div>
						<span class="text-sm font-semibold text-gray-900">AI Screening</span>
					</div>
					<span class="text-[10px] text-gray-400 bg-gray-100 px-1.5 py-0.5 rounded">Automated</span>
				</div>
				<div class="p-3 space-y-2">
					<div class="flex items-center gap-2 text-xs text-gray-600">
						<div class="w-4 h-4 flex items-center justify-center text-gray-400">Aa</div>
						<span>Language Skills</span>
					</div>
					<div class="flex items-center gap-2 text-xs text-gray-600">
						<div class="w-4 h-4 flex items-center justify-center text-gray-400">@</div>
						<span>Screening Score</span>
					</div>
					<div class="flex items-center gap-2 text-xs text-gray-600">
						<div class="w-4 h-4 flex items-center justify-center text-gray-400">#</div>
						<span>Duration</span>
					</div>
					<div class="text-[10px] text-gray-400 pl-6">+ 3 More Attributes</div>
				</div>
			</div>

			<!-- Reference Object -->
			<div class="absolute top-10 right-10 w-64 bg-white rounded-lg border border-gray-200 shadow-sm z-10">
				<div class="p-3 border-b border-gray-100 flex items-center justify-between bg-gray-50/50 rounded-t-lg">
					<div class="flex items-center gap-2">
						<div class="w-6 h-6 rounded bg-purple-100 flex items-center justify-center text-purple-600">
							<ShieldCheck size={14} />
						</div>
						<span class="text-sm font-semibold text-gray-900">References</span>
					</div>
					<span class="text-[10px] text-gray-400 bg-gray-100 px-1.5 py-0.5 rounded">Verified</span>
				</div>
				<div class="p-3 space-y-2">
					<div class="flex items-center gap-2 text-xs text-gray-600">
						<div class="w-4 h-4 flex items-center justify-center text-gray-400">Aa</div>
						<span>Referee Name</span>
					</div>
					<div class="flex items-center gap-2 text-xs text-gray-600">
						<div class="w-4 h-4 flex items-center justify-center text-gray-400">□</div>
						<span>Verification Status</span>
					</div>
					<div class="flex items-center gap-2 text-xs text-gray-600">
						<div class="w-4 h-4 flex items-center justify-center text-gray-400">≡</div>
						<span>Sentiment Analysis</span>
					</div>
					<div class="text-[10px] text-gray-400 pl-6">+ 2 More Attributes</div>
				</div>
			</div>

			<!-- Candidate Object (Center) -->
			<div class="absolute top-60 left-1/2 -translate-x-full -ml-4 w-64 bg-white rounded-lg border border-gray-200 shadow-sm z-10">
				<div class="p-3 border-b border-gray-100 flex items-center justify-between bg-gray-50/50 rounded-t-lg">
					<div class="flex items-center gap-2">
						<div class="w-6 h-6 rounded bg-green-100 flex items-center justify-center text-green-600">
							<User size={14} />
						</div>
						<span class="text-sm font-semibold text-gray-900">Candidate</span>
					</div>
					<span class="text-[10px] text-gray-400 bg-gray-100 px-1.5 py-0.5 rounded">ATS Sync</span>
				</div>
				<div class="p-3 space-y-2">
					<div class="flex items-center gap-2 text-xs text-gray-600">
						<div class="w-4 h-4 flex items-center justify-center text-gray-400">Aa</div>
						<span>Full Name</span>
					</div>
					<div class="flex items-center gap-2 text-xs text-gray-600">
						<div class="w-4 h-4 flex items-center justify-center text-gray-400">@</div>
						<span>Email Address</span>
					</div>
					<div class="flex items-center gap-2 text-xs text-gray-600">
						<Building2 size={14} class="text-gray-400" />
						<span>Current Company</span>
					</div>
					<div class="text-[10px] text-gray-400 pl-6">+ 12 More Attributes</div>
				</div>
			</div>

			<!-- Add Custom Flow -->
			<div class="absolute top-60 left-1/2 ml-4 w-64 h-40 border-2 border-dashed border-blue-200 rounded-lg flex items-center justify-center bg-blue-50/30 z-10">
				<div class="flex items-center gap-2 text-blue-500 font-medium text-sm">
					<Plus size={16} /> Add custom flow
				</div>
			</div>
		</div>

		<!-- Table View at Bottom -->
		<div class="mt-10 bg-white border border-gray-200 rounded-lg shadow-sm overflow-hidden max-w-4xl mx-auto">
			<div class="grid grid-cols-4 gap-4 p-3 border-b border-gray-100 bg-gray-50 text-[11px] font-medium text-gray-500">
				<div class="flex items-center gap-2"><User size={12} /> Candidate</div>
				<div class="flex items-center gap-2"><CheckSquare size={12} /> Assessment</div>
				<div class="flex items-center gap-2"><Phone size={12} /> Screening</div>
				<div class="flex items-center gap-2"><ShieldCheck size={12} /> References</div>
			</div>
			<!-- Row 1 -->
			<div class="grid grid-cols-4 gap-4 p-3 border-b border-gray-50 text-xs hover:bg-gray-50">
				<div class="flex items-center gap-2"><div class="w-5 h-5 rounded-full bg-gray-200 overflow-hidden"><img src="https://i.pravatar.cc/150?u=11" alt="" class="w-full h-full object-cover"/></div> Albert Lund</div>
				<div><span class="bg-green-100 text-green-700 px-1.5 py-0.5 rounded text-[10px]">92% Match</span></div>
				<div><span class="text-blue-600 underline decoration-blue-200">Completed</span></div>
				<div><span class="bg-blue-100 text-blue-700 px-1.5 py-0.5 rounded text-[10px]">Verified</span></div>
			</div>
			<!-- Row 2 -->
			<div class="grid grid-cols-4 gap-4 p-3 border-b border-gray-50 text-xs hover:bg-gray-50">
				<div class="flex items-center gap-2"><div class="w-5 h-5 rounded-full bg-gray-200 overflow-hidden"><img src="https://i.pravatar.cc/150?u=12" alt="" class="w-full h-full object-cover"/></div> Jenna Roberts</div>
				<div><span class="bg-green-100 text-green-700 px-1.5 py-0.5 rounded text-[10px]">88% Match</span></div>
				<div><span class="text-blue-600 underline decoration-blue-200">Completed</span></div>
				<div><span class="bg-blue-100 text-blue-700 px-1.5 py-0.5 rounded text-[10px]">Verified</span></div>
			</div>
			<!-- Row 3 -->
			<div class="grid grid-cols-4 gap-4 p-3 border-b border-gray-50 text-xs hover:bg-gray-50">
				<div class="flex items-center gap-2"><div class="w-5 h-5 rounded-full bg-gray-200 overflow-hidden"><img src="https://i.pravatar.cc/150?u=13" alt="" class="w-full h-full object-cover"/></div> David Chen</div>
				<div><span class="bg-orange-100 text-orange-700 px-1.5 py-0.5 rounded text-[10px]">74% Match</span></div>
				<div><span class="text-blue-600 underline decoration-blue-200">Completed</span></div>
				<div><span class="text-gray-400">Pending</span></div>
			</div>
			<!-- Row 4 -->
			<div class="grid grid-cols-4 gap-4 p-3 text-xs hover:bg-gray-50">
				<div class="flex items-center gap-2"><div class="w-5 h-5 rounded-full bg-gray-200 overflow-hidden"><img src="https://i.pravatar.cc/150?u=14" alt="" class="w-full h-full object-cover"/></div> Marc Lopez</div>
				<div><span class="bg-green-100 text-green-700 px-1.5 py-0.5 rounded text-[10px]">95% Match</span></div>
				<div><span class="text-blue-600 underline decoration-blue-200">Completed</span></div>
				<div><span class="bg-blue-100 text-blue-700 px-1.5 py-0.5 rounded text-[10px]">Verified</span></div>
			</div>
		</div>
	</div>
</section>
