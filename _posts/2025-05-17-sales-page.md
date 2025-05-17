---
title: Sales Page
---
import React from "react";

import { Button } from "@/components/ui/button";

export default function HomePage() {

return (

<div className="bg-black text-white min-h-screen font-sans">

<header className="text-center py-4 bg-gradient-to-b from-black to-gray-900">

<p className="text-orange-400 font-bold">

⭐ For Anyone Looking to <span className="underline">Build a High Profit Digital Product</span>

</p>

<h1 className="text-3xl md:text-5xl font-extrabold leading-tight my-4">

AVERAGE PEOPLE ARE NOW MAKING THOUSANDS WITH THIS NEW <br />

"EXTRACTION PROMPT" ALLOWING THEM TO CREATE AND SELL PRODUCTS IN A DAY!

</h1>

<p className="text-xl mt-2">

Using The Same System That Made Me $65,694 In 23 Days!

</p>

</header>

<main className="max-w-6xl mx-auto p-6 grid md:grid-cols-3 gap-8">

<div className="md:col-span-2">

<div className="relative pb-9/16">

<div className="aspect-w-16 aspect-h-9">

<div className="bg-gray-800 flex items-center justify-center">

<p>Your Video Is Playing<br />Click To Unmute</p>

</div>

</div>

</div>

<div className="my-6">

<Button className="bg-orange-500 hover:bg-orange-600 text-white text-lg px-6 py-3 rounded-xl">

Join The 7-Figure Product Extraction Prompt

</Button>

<p className="text-sm text-gray-400 mt-2">100% Secure. 256-Bit Security Encryption</p>

</div>

<section className="mt-6 space-y-4">

<p>

There are two types of solopreneurs that will see this page: those who spend months looking around hoping their future will just "happen," and those that realize NOW is their moment and take action to build their future.

</p>

<p>

I bet you already know which type gets ahead...

</p>

<p>

If you're like most aspiring entrepreneurs, you're probably sick and tired of sitting on ideas that you know could make money — but not knowing how to turn that idea into a digital, scalable, high simple product.

</p>

<ul className="list-disc list-inside space-y-2 mt-4">

<li>Struggling to create a profitable digital product...</li>

<li>Watching others launch simple products and make 6-figures...</li>

<li>Feeling overwhelmed by complex marketing funnels...</li>

<li>Worried that you're missing the golden window of opportunity...</li>

<li>Frustrated because every idea you have feels incomplete...</li>

</ul>

<p>

And the worst part? Every day that goes by, someone else is launching a product you could have created...

</p>

</section>

<Button className="mt-6 bg-yellow-400 hover:bg-yellow-500 text-black text-lg px-6 py-3 rounded-xl">

⬇ See The Full Page here ⬇

</Button>

</div>

<aside className="bg-white text-black p-6 rounded-xl shadow-xl">

<h2 className="text-xl font-bold text-center mb-4">JOIN NOW FOR $27</h2>

<div className="space-y-4">

<img src="/mockup-products.png" alt="Product Bundle" className="rounded-lg" />

<div>

<p className="font-semibold">Step #1</p>

<p>Contact Details</p>

</div>

<div>

<p className="font-semibold">Step #2</p>

<p>Billing Info</p>

</div>

<input

type="text"

placeholder="Full Name..."

className="w-full p-2 border border-gray-300 rounded"

/>

</div>

</aside>

</main>

<footer className="text-center text-sm text-gray-400 py-6">

<p>Copyright © 2025 | Wealtherly | All Rights Reserved</p>

<p className="mt-2 max-w-2xl mx-auto">

This site is not a part of the Facebook™ website or Facebook Inc. Additionally, this site is NOT endorsed by Facebook™ in any way. FACEBOOK™ is a trademark of FACEBOOK™, Inc.

</p>

</footer>

</div>

);

}