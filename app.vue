<template>
	<div class="flex h-screen justify-center items-center flex-col">
		<h3 class="text-xl text-gray-900 font-medium mb-3">
			Add data to your report
		</h3>
		<p class="mb-4">
			Once loaded, your data will appear in the <b>Data</b> pane.
		</p>
		<div class="flex gap-3 mb-4">
			<div
				class="w-[10rem] shadow bg-green-100 h-[8rem] flex justify-center items-center flex-col">
				<div class="flex-1 flex justify-center items-center">
					<img src="./public/excel.png" alt="Excel" />
				</div>
				<p class="bg-white pl-3 w-full text-[.6rem] h-[30%] flex items-center">
					Import data from Excel
				</p>
			</div>
			<div
				class="w-[10rem] shadow bg-purple-100 h-[8rem] flex justify-center items-center flex-col">
				<div class="flex-1 flex justify-center items-center">
					<img src="./public/sql.png" alt="Sql server" />
				</div>
				<p class="bg-white pl-3 w-full text-[.6rem] h-[30%] flex items-center">
					Import data from Sql Server
				</p>
			</div>
			<div
				class="w-[10rem] shadow bg-yellow-100 h-[8rem] flex justify-center items-center flex-col">
				<div class="flex-1 flex justify-center items-center">
					<img src="./public/paste.png" alt="paste data" />
				</div>
				<p class="bg-white pl-3 w-full text-[.6rem] h-[30%] flex items-center">
					Paste data into Blank table
				</p>
			</div>
			<div
				class="w-[10rem] shadow bg-slate-100 h-[8rem] flex justify-center items-center flex-col">
				<div class="flex-1 flex justify-center items-center">
					<img src="./public/server.png" alt="sample data" />
				</div>
				<p class="bg-white pl-3 w-full text-[.6rem] h-[30%] flex items-center">
					Use sample data
				</p>
			</div>
		</div>
		<p class="text-green-700 font-medium text-xs">
			Get data from another source ->
		</p>
	</div>
</template>
