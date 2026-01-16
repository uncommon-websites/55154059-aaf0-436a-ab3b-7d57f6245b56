<script lang="ts">
	import { X } from 'lucide-svelte';
</script>

<div class="fixed top-0 left-0 right-0 z-50">
	<!-- Top Banner -->
	<div class="bg-black text-white text-xs font-medium py-2.5 px-4 relative text-center">
		<div class="flex justify-center items-center gap-2">
			<span>New: 2025 Talent Report on pre-employment screening</span>
			<span class="opacity-70">→</span>
		</div>
		<button class="absolute right-4 top-1/2 -translate-y-1/2 text-white/60 hover:text-white">
			<X size={14} />
		</button>
	</div>

	<!-- Main Nav -->
	<nav class="bg-white/90 backdrop-blur-md border-b border-gray-200">
		<div class="max-w-[1400px] mx-auto px-6 h-16 flex items-center justify-between">
			<div class="flex items-center gap-8">
				<a href="/" class="flex items-center gap-2 text-black hover:opacity-80 transition-opacity">
					<div class="w-8 h-8 bg-black rounded-lg flex items-center justify-center">
						<span class="text-white font-bold text-xl">H</span>
					</div>
					<span class="font-bold text-xl tracking-tight">HiPeople</span>
				</a>

				<div class="hidden md:flex items-center gap-6 text-sm font-medium text-gray-600">
					<button class="hover:text-black flex items-center gap-1">
						Product <span class="text-[10px]">▼</span>
					</button>
					<button class="hover:text-black flex items-center gap-1">
						Solutions <span class="text-[10px]">▼</span>
					</button>
					<button class="hover:text-black flex items-center gap-1">
						Resources <span class="text-[10px]">▼</span>
					</button>
					<a href="#" class="hover:text-black">Pricing</a>
				</div>
			</div>

			<div class="flex items-center gap-4">
				<a href="#" class="text-sm font-medium text-gray-600 hover:text-black">Sign in</a>
				<a href="#" class="bg-black text-white text-sm font-medium px-4 py-2 rounded-lg hover:bg-gray-800 transition-colors">
					Book a demo
				</a>
			</div>
		</div>
	</nav>
</div>
