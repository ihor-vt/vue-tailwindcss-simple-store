<template>
    <header class="flex justify-between border-b border-slate-200 px-10 py-8">

        <div class="flex items-center gap-4">
            <img src="/logo.png" alt="Logo" class="w-10">
            <div>
                <h2 class="text-xl font-bold uppercase">Vue Sneakers</h2>
                <p class="text-slate-500">The best sneaker store</p>
            </div>
        </div>

        <ul class="flex item-center gap-10">
            <li class="flex items-center cursor-pointer gap-3 text-gray-500 hover:text-black">
                <img src="/cart.svg" alt="Cart">
                <b>$ 40</b>
            </li>

            <li class="flex items-center cursor-pointer gap-3 text-gray-500 hover:text-black">
                <img src="/heart.svg" alt="Bookmarks">
                <span>Bookmarks</span>
            </li>

            <li class="flex items-center cursor-pointer gap-3 text-gray-500 hover:text-black">
                <img src="/profile.svg" alt="Profile">
                <span>Profile</span>
            </li>
        </ul>
    </header>
</template>
