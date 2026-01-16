<script lang="ts">
	import { ArrowRight, Zap, Bot, Database, BarChart3, Mail, MessageSquare, Calendar, CheckCircle2, Search, Plus, MoreHorizontal, Phone, ShieldCheck } from 'lucide-svelte';
</script>

<section class="max-w-[1200px] mx-auto px-6 py-20">
	<div class="mb-20 max-w-2xl">
		<h2 class="text-4xl font-serif text-gray-900 mb-6">
			Talent Intelligence at scale. <span class="text-gray-500 font-sans text-xl font-normal block mt-4">Execute your hiring strategy with precision. Design powerful screening flows, deploy AI agents, and build detailed quality reports — all in one platform.</span>
		</h2>
	</div>

	<div class="border border-gray-200 rounded-xl overflow-hidden bg-white shadow-sm">
		<!-- Row 1: AI Screening -->
		<div class="grid grid-cols-1 md:grid-cols-3 border-b border-gray-200">
			<div class="p-12 flex flex-col justify-between border-r border-gray-200">
				<div>
					<h3 class="text-xl font-bold text-gray-900 mb-4">24/7 AI Screening</h3>
					<p class="text-gray-500 leading-relaxed mb-8">
						Conduct screening calls in 113 languages at any time. Save 12 recruiter hours per week on initial phone screens.
					</p>
				</div>
				<a href="#" class="inline-flex items-center gap-2 text-sm font-medium text-gray-900 hover:opacity-70 transition-opacity">
					Explore AI Screening <ArrowRight size={16} />
				</a>
			</div>
			<div class="col-span-2 bg-gray-50/50 p-12 flex items-center justify-center overflow-hidden relative">
				<!-- Workflow Diagram Mockup -->
				<div class="relative w-full max-w-lg">
					<!-- Trigger -->
					<div class="absolute top-0 left-0 bg-white border border-gray-200 rounded-lg p-3 shadow-sm w-64 z-10">
						<div class="flex items-center gap-2 text-xs font-medium text-gray-500 mb-2">
							<Zap size={12} /> Workflow
						</div>
						<div class="text-sm font-medium text-gray-900">New Application Received</div>
						<div class="text-xs text-gray-400 mt-1">Triggered from Greenhouse ATS</div>
					</div>

					<!-- Path -->
					<svg class="absolute top-16 left-32 w-full h-40 pointer-events-none" style="z-index: 0;">
						<path d="M 0 0 V 20 H 100 V 40" fill="none" stroke="#e5e7eb" stroke-width="2" />
						<path d="M 0 0 V 20 H -100 V 40" fill="none" stroke="#e5e7eb" stroke-width="2" />
					</svg>

					<!-- Branch 1 -->
					<div class="absolute top-32 -left-20 bg-white border border-gray-200 rounded-lg p-3 shadow-sm w-56">
						<div class="flex items-center gap-2 text-xs font-medium text-gray-500 mb-2">
							<Bot size={12} /> AI Agent
						</div>
						<div class="text-sm font-medium text-gray-900">Schedule Screening Call</div>
						<div class="mt-2 flex gap-2">
							<span class="px-2 py-0.5 bg-blue-100 text-blue-700 text-[10px] rounded">Automatic</span>
						</div>
					</div>

					<!-- Branch 2 -->
					<div class="absolute top-32 left-40 bg-white border border-gray-200 rounded-lg p-3 shadow-sm w-56">
						<div class="flex items-center gap-2 text-xs font-medium text-gray-500 mb-2">
							<ShieldCheck size={12} /> Fraud Check
						</div>
						<div class="text-sm font-medium text-gray-900">Verify Identity</div>
						<div class="flex items-center gap-2 mt-2">
							<div class="w-4 h-4 rounded bg-green-100 flex items-center justify-center text-[10px] text-green-600">✓</div>
							<span class="text-xs text-gray-500">No cheating detected</span>
						</div>
					</div>
				</div>
				
				<!-- Decorative geometric shape -->
				<div class="absolute bottom-10 right-10 opacity-20">
					<svg width="100" height="100" viewBox="0 0 100 100" fill="none">
						<path d="M50 0L93.3013 25V75L50 100L6.69873 75V25L50 0Z" stroke="black" stroke-width="1"/>
						<path d="M50 0V50M93.3013 25L50 50M93.3013 75L50 50M50 100V50M6.69873 75L50 50M6.69873 25L50 50" stroke="black" stroke-width="1"/>
					</svg>
				</div>
			</div>
		</div>

		<!-- Row 2: Scientific Assessments -->
		<div class="grid grid-cols-1 md:grid-cols-3 border-b border-gray-200">
			<div class="p-12 flex flex-col justify-between border-r border-gray-200">
				<div>
					<h3 class="text-xl font-bold text-gray-900 mb-4">Scientific Assessments</h3>
					<p class="text-gray-500 leading-relaxed mb-8">
						Grounded in leading science, our assessments help you identify top talent with confidence. Move candidates forward 2-4 days faster.
					</p>
				</div>
				<a href="#" class="inline-flex items-center gap-2 text-sm font-medium text-gray-900 hover:opacity-70 transition-opacity">
					Explore Assessments <ArrowRight size={16} />
				</a>
			</div>
			<div class="col-span-2 bg-gray-50/50 p-12 flex items-center justify-center relative">
				<div class="bg-white rounded-xl shadow-sm border border-gray-200 w-full max-w-md overflow-hidden">
					<div class="p-3 border-b border-gray-100 flex items-center gap-2 bg-gray-50/50">
						<BarChart3 size={16} class="text-blue-600" />
						<span class="text-xs font-medium text-gray-700">Assessment Report: Senior Engineer</span>
					</div>
					<div class="p-4 space-y-4">
						<div class="flex gap-3">
							<div class="w-8 h-8 rounded-full bg-blue-100 flex items-center justify-center flex-shrink-0 font-bold text-blue-600 text-xs">
								A+
							</div>
							<div class="flex-1">
								<div class="bg-gray-50 rounded-lg p-3 text-sm text-gray-800 mb-2">
									<p class="font-medium mb-1">Technical Proficiency</p>
									<div class="w-full bg-gray-200 h-1.5 rounded-full overflow-hidden">
										<div class="bg-blue-600 h-full w-[92%]"></div>
									</div>
								</div>
								
								<div class="bg-white border border-gray-200 rounded-lg p-3 text-sm text-gray-800 mb-2 shadow-sm">
									<div class="flex items-center gap-2 mb-2">
										<span class="font-medium">Cognitive Ability</span>
									</div>
									<p class="text-gray-500 text-xs">Strong problem-solving skills and logical reasoning.</p>
								</div>
							</div>
						</div>
					</div>
				</div>
				
				<!-- Decorative geometric shape -->
				<div class="absolute bottom-10 right-10 opacity-20">
					<svg width="100" height="100" viewBox="0 0 100 100" fill="none">
						<circle cx="50" cy="50" r="40" stroke="black" stroke-width="1"/>
						<path d="M50 10 C 70 30, 70 70, 50 90 C 30 70, 30 30, 50 10" stroke="black" stroke-width="1" fill="none"/>
						<path d="M10 50 C 30 30, 70 30, 90 50 C 70 70, 30 70, 10 50" stroke="black" stroke-width="1" fill="none"/>
					</svg>
				</div>
			</div>
		</div>

		<!-- Row 3: Reference Checks -->
		<div class="grid grid-cols-1 md:grid-cols-3 border-b border-gray-200">
			<div class="p-12 flex flex-col justify-between border-r border-gray-200">
				<div>
					<h3 class="text-xl font-bold text-gray-900 mb-4">Automated References</h3>
					<p class="text-gray-500 leading-relaxed mb-8">
						Complete reference checks in as little as 25 hours. Cut 2-3 hours of manual work per candidate.
					</p>
				</div>
				<a href="#" class="inline-flex items-center gap-2 text-sm font-medium text-gray-900 hover:opacity-70 transition-opacity">
					Explore References <ArrowRight size={16} />
				</a>
			</div>
			<div class="col-span-2 bg-gray-50/50 p-12 flex items-center justify-center relative">
				<div class="relative w-full max-w-md h-64 flex items-center justify-center">
					<!-- Center Logo -->
					<div class="w-16 h-16 bg-black rounded-xl flex items-center justify-center z-10 shadow-lg">
						<span class="text-white font-bold text-2xl">H</span>
					</div>

					<!-- Connecting Lines -->
					<svg class="absolute inset-0 w-full h-full pointer-events-none">
						<line x1="50%" y1="50%" x2="20%" y2="20%" stroke="#e5e7eb" stroke-width="1" />
						<line x1="50%" y1="50%" x2="80%" y2="20%" stroke="#e5e7eb" stroke-width="1" />
						<line x1="50%" y1="50%" x2="20%" y2="80%" stroke="#e5e7eb" stroke-width="1" />
						<line x1="50%" y1="50%" x2="80%" y2="80%" stroke="#e5e7eb" stroke-width="1" />
					</svg>

					<!-- Icons -->
					<div class="absolute top-10 left-20 bg-white p-2 rounded-lg shadow-sm border border-gray-100">
						<Users size={20} class="text-blue-500" />
					</div>
					<div class="absolute top-10 right-20 bg-white p-2 rounded-lg shadow-sm border border-gray-100">
						<Mail size={20} class="text-green-500" />
					</div>
					<div class="absolute bottom-10 left-20 bg-white p-2 rounded-lg shadow-sm border border-gray-100">
						<Phone size={20} class="text-red-500" />
					</div>
					<div class="absolute bottom-10 right-20 bg-white p-2 rounded-lg shadow-sm border border-gray-100">
						<CheckCircle2 size={20} class="text-purple-500" />
					</div>
				</div>
				
				<!-- Decorative geometric shape -->
				<div class="absolute bottom-10 right-10 opacity-20">
					<svg width="100" height="100" viewBox="0 0 100 100" fill="none">
						<rect x="25" y="25" width="50" height="50" stroke="black" stroke-width="1" transform="rotate(45 50 50)"/>
						<rect x="25" y="25" width="50" height="50" stroke="black" stroke-width="1"/>
					</svg>
				</div>
			</div>
		</div>

		<!-- Row 4: ATS Integration -->
		<div class="grid grid-cols-1 md:grid-cols-3">
			<div class="p-12 flex flex-col justify-between border-r border-gray-200">
				<div>
					<h3 class="text-xl font-bold text-gray-900 mb-4">Native ATS Sync</h3>
					<p class="text-gray-500 leading-relaxed mb-8">
						Deep integrations with Greenhouse, Lever, Workday, and more. Bi-directional, real-time sync keeps your data accurate.
					</p>
				</div>
				<a href="#" class="inline-flex items-center gap-2 text-sm font-medium text-gray-900 hover:opacity-70 transition-opacity">
					Explore Integrations <ArrowRight size={16} />
				</a>
			</div>
			<div class="col-span-2 bg-gray-50/50 p-12 flex items-center justify-center relative">
				<div class="grid grid-cols-2 gap-6 w-full max-w-lg">
					<!-- Chart 1 -->
					<div class="bg-white p-4 rounded-xl border border-gray-200 shadow-sm">
						<div class="flex items-center justify-between mb-4">
							<div class="text-xs font-medium text-gray-500">Hiring Velocity</div>
							<MoreHorizontal size={14} class="text-gray-400" />
						</div>
						<div class="h-32 flex items-end gap-2 justify-between px-2">
							<div class="w-full bg-blue-100 h-[40%] rounded-t-sm"></div>
							<div class="w-full bg-blue-200 h-[60%] rounded-t-sm"></div>
							<div class="w-full bg-blue-300 h-[30%] rounded-t-sm"></div>
							<div class="w-full bg-blue-400 h-[80%] rounded-t-sm"></div>
							<div class="w-full bg-blue-500 h-[90%] rounded-t-sm"></div>
						</div>
					</div>

					<!-- List -->
					<div class="bg-white p-4 rounded-xl border border-gray-200 shadow-sm space-y-3">
						<div class="flex items-center justify-between mb-2">
							<div class="text-xs font-medium text-gray-500">Connected ATS</div>
						</div>
						<div class="flex items-center gap-2 text-xs">
							<div class="w-2 h-2 rounded-full bg-green-500"></div>
							<span class="flex-1">Greenhouse</span>
							<span class="text-gray-400">Live</span>
						</div>
						<div class="flex items-center gap-2 text-xs">
							<div class="w-2 h-2 rounded-full bg-blue-500"></div>
							<span class="flex-1">Lever</span>
							<span class="text-gray-400">Live</span>
						</div>
						<div class="flex items-center gap-2 text-xs">
							<div class="w-2 h-2 rounded-full bg-orange-500"></div>
							<span class="flex-1">Workday</span>
							<span class="text-gray-400">Live</span>
						</div>
					</div>
				</div>
				
				<!-- Decorative geometric shape -->
				<div class="absolute bottom-10 right-10 opacity-20">
					<svg width="100" height="100" viewBox="0 0 100 100" fill="none">
						<path d="M20 80 L 50 30 L 80 80 Z" stroke="black" stroke-width="1"/>
						<path d="M20 80 L 20 50 L 50 30" stroke="black" stroke-width="1"/>
						<path d="M80 80 L 80 50 L 50 30" stroke="black" stroke-width="1"/>
					</svg>
				</div>
			</div>
		</div>
	</div>
</section>
