---
title: "Contributing to Open Source with Cursor"
info: |
   "Contributing to Open Source with Cursor"
class: bg-[#0F0F0F] text-white
mdc: true
theme: default
layout: cover
background: '#0F0F0F'
transition: slide-left
---

<!-- TODO: add the game -->
<div class="flex flex-col items-center justify-center h-full gap-8">
  <h2 class="text-3xl font-bold text-white mb-4">Scan to ask questions</h2>
  <div class="w-52 h-52 bg-white rounded-lg flex items-center justify-center overflow-hidden">
    <img src="/assets/misc/qr_code_qa.jpg" alt="QR Code for Q&A" class="w-full h-full object-cover" />
  </div>
</div>


---
layout: center
class: text-center
transition: slide-up
---
<!-- <div class="absolute left-8 top-1/6 transform -translate-y-1/2">
    <img src="/assets/brand/cursor_riyadh_old.jpeg" alt="Cursor Logo" class="w-40 h-40 rounded-full hover:scale-105 transition-transform duration-300" />
</div> -->

<div class="flex flex-col items-center gap-8">
  <h1 class="text-6xl font-bold tracking-tight text-white">Contributing to Open Source with Cursor</h1>
  <h2 class="text-3xl text-[#6E6E6E]">December 25, 2025</h2>
</div>

---
layout: center
class: text-center
---

# Agenda

<div class="max-w-2xl mx-auto">
  <div v-click="1" class="grid grid-cols-1 gap-4">  
    <div class="bg-[#171717] border border-[#252525] rounded-lg p-3 hover:bg-[#1F1F1F] transition-colors">
      <div class="flex justify-between items-center">
        <span class="font-semibold text-lg">🚀 Workshop</span>
      </div>
    </div>
    <div class="bg-[#171717] border border-[#252525] rounded-lg p-3 hover:bg-[#1F1F1F] transition-colors">
      <div class="flex justify-between items-center">
        <span class="font-semibold text-lg">❓ Q/A</span>
      </div>
    </div>
    <div class="bg-[#171717] border border-[#252525] rounded-lg p-3 hover:bg-[#1F1F1F] transition-colors">
      <div class="flex justify-between items-center">
        <span class="font-semibold text-lg">💻 Hackathon</span>
      </div>
    </div>
    <div class="bg-[#171717] border border-[#252525] rounded-lg p-3 hover:bg-[#1F1F1F] transition-colors">
      <div class="flex justify-between items-center">
        <span class="font-semibold text-lg">👥 Networking</span>
      </div>
    </div>
    <div class="bg-[#171717] border border-[#252525] rounded-lg p-3 hover:bg-[#1F1F1F] transition-colors">
      <div class="flex justify-between items-center">
        <span class="font-semibold text-lg">🎉 End</span>
      </div>
    </div>
  </div>
</div>

---
layout: center
class: px-8
transition: slide-up
---

<div class="flex flex-col items-center space-y-6 mt-8">
  <div class="w-48 h-48 bg-[#171717] border border-[#252525] rounded-full flex items-center justify-center">
    <!-- TODO: Add Usman's profile image to /assets/speakers/usman.jpeg -->
    <img src="https://media.licdn.com/dms/image/v2/D4D03AQEWMfX035h84A/profile-displayphoto-shrink_800_800/B4DZTbny9EGkAg-/0/1738851430743?e=1768435200&v=beta&t=OUJB09GRV5Jx2nx3q65GHUKm_5SezSj9p7sQ00VT-JQ" class="w-full h-full object-cover rounded-full" />
  </div>
  
  <div class="text-center space-y-4 max-w-2xl">
      <h2 class="text-2xl text-white font-semibold">Usman Siddique</h2>
      <p class="text-xl">Software Engineer at <span class="text-white font-semibold">Motive</span></p>
  </div>
</div>

---
layout: center
class: px-8
transition: slide-up
---

# An Analogy: Getting Across Town 🏙️

<div class="mt-6 mb-4 text-center text-[#6E6E6E] text-lg">
  Imagine you need to get across town. There are many ways to do it...
</div>

<div class="grid grid-cols-3 gap-6 mt-8">
  <div v-click class="bg-[#171717] border border-[#252525] rounded-lg p-6 text-center hover:scale-105 transition-transform duration-300">
    <div class="text-6xl mb-4">🚶</div>
    <h3 class="text-xl font-bold mb-3 text-white">Walking</h3>
    <div class="space-y-2 text-left">
      <div class="flex items-center gap-2 text-sm">
        <span class="text-green-400">💰</span>
        <span class="text-[#6E6E6E]">Free</span>
      </div>
      <div class="flex items-center gap-2 text-sm">
        <span class="text-red-400">⏱️</span>
        <span class="text-[#6E6E6E]">Takes longest</span>
      </div>
      <div class="flex items-center gap-2 text-sm">
        <span class="text-yellow-400">💪</span>
        <span class="text-[#6E6E6E]">Most effort</span>
      </div>
    </div>
  </div>
  
  <div v-click class="bg-[#171717] border border-[#252525] rounded-lg p-6 text-center hover:scale-105 transition-transform duration-300">
    <div class="text-6xl mb-4">🚲</div>
    <h3 class="text-xl font-bold mb-3 text-white">Biking</h3>
    <div class="space-y-2 text-left">
      <div class="flex items-center gap-2 text-sm">
        <span class="text-yellow-400">💰</span>
        <span class="text-[#6E6E6E]">Some cost</span>
      </div>
      <div class="flex items-center gap-2 text-sm">
        <span class="text-yellow-400">⏱️</span>
        <span class="text-[#6E6E6E]">Faster</span>
      </div>
      <div class="flex items-center gap-2 text-sm">
        <span class="text-yellow-400">💪</span>
        <span class="text-[#6E6E6E]">Moderate effort</span>
      </div>
    </div>
  </div>
  
  <div v-click class="bg-[#171717] border border-[#252525] rounded-lg p-6 text-center hover:scale-105 transition-transform duration-300">
    <div class="text-6xl mb-4">🚗</div>
    <h3 class="text-xl font-bold mb-3 text-white">Driving</h3>
    <div class="space-y-2 text-left">
      <div class="flex items-center gap-2 text-sm">
        <span class="text-red-400">💰</span>
        <span class="text-[#6E6E6E]">Most expensive</span>
      </div>
      <div class="flex items-center gap-2 text-sm">
        <span class="text-green-400">⏱️</span>
        <span class="text-[#6E6E6E]">Fastest</span>
      </div>
      <div class="flex items-center gap-2 text-sm">
        <span class="text-green-400">💪</span>
        <span class="text-[#6E6E6E]">Least effort</span>
      </div>
    </div>
  </div>
</div>

<div v-click class="mt-8 text-center">
  <div class="inline-block bg-[#171717] border border-[#252525] rounded-lg px-6 py-3">
    <span class="text-lg">🤔 You have the choice between <span class="font-bold text-white">time</span>, <span class="font-bold text-white">money</span>, <span class="font-bold text-white">reliability</span>, and <span class="font-bold text-white">effort</span></span>
  </div>
</div>

---
layout: center
class: px-8
transition: slide-up
---

# Similarly: Building Software 💻

<div class="grid grid-cols-3 gap-4 mt-6">
  <div v-click class="bg-[#171717] border border-[#252525] rounded-lg p-4 text-center">
    <div class="text-4xl mb-2">📝</div>
    <h3 class="text-lg font-bold mb-2 text-white">No Tools</h3>
    <div class="space-y-1 text-left text-xs">
      <div class="flex items-center gap-2">
        <span class="text-green-400">💰</span>
        <span class="text-[#6E6E6E]">Free</span>
      </div>
      <div class="flex items-center gap-2">
        <span class="text-red-400">⏱️</span>
        <span class="text-[#6E6E6E]">Slowest</span>
      </div>
      <div class="flex items-center gap-2">
        <span class="text-red-400">⚠️</span>
        <span class="text-[#6E6E6E]">More errors</span>
      </div>
    </div>
  </div>
  
  <div v-click class="bg-[#171717] border border-[#252525] rounded-lg p-4 text-center">
    <div class="text-4xl mb-2">🛠️</div>
    <h3 class="text-lg font-bold mb-2 text-white">IDE & Tooling</h3>
    <div class="space-y-1 text-left text-xs">
      <div class="flex items-center gap-2">
        <span class="text-yellow-400">💰</span>
        <span class="text-[#6E6E6E]">Some cost</span>
      </div>
      <div class="flex items-center gap-2">
        <span class="text-yellow-400">⏱️</span>
        <span class="text-[#6E6E6E]">Faster</span>
      </div>
      <div class="flex items-center gap-2">
        <span class="text-green-400">✅</span>
        <span class="text-[#6E6E6E]">Feedback</span>
      </div>
    </div>
  </div>
  
  <div v-click class="bg-[#171717] border border-white rounded-lg p-4 text-center">
    <div class="text-4xl mb-2">🤖</div>
    <h3 class="text-lg font-bold mb-2 text-white">AI Tooling</h3>
    <div class="space-y-1 text-left text-xs">
      <div class="flex items-center gap-2">
        <span class="text-red-400">💰</span>
        <span class="text-[#6E6E6E]">Costs more</span>
      </div>
      <div class="flex items-center gap-2">
        <span class="text-green-400">⏱️</span>
        <span class="text-[#6E6E6E]">Fastest</span>
      </div>
      <div class="flex items-center gap-2">
        <span class="text-yellow-400">🎯</span>
        <span class="text-[#6E6E6E]">Practice needed</span>
      </div>
    </div>
  </div>
</div>

<div v-click class="mt-6 text-center">
  <div class="inline-block bg-[#171717] border border-[#252525] rounded-lg px-6 py-3">
    <span class="text-lg">🚀 AI tools help you build <span class="font-bold text-white">faster</span> with <span class="font-bold text-white">practice</span></span>
  </div>
</div>

---
layout: center
class: px-8
transition: slide-up
---

# Cursor

---
layout: center
class: px-8
---

# AI Models = Super Intelligent APIs

<div class="grid grid-cols-3 gap-6 mt-8">
  <div v-click class="bg-[#171717] border border-[#252525] rounded-lg p-6 text-center">
    <div class="text-4xl mb-4">💳</div>
    <h3 class="text-xl font-bold mb-2">Stripe API</h3>
    <p class="text-sm text-[#6E6E6E] mb-4">Handle payments</p>
    <div class="bg-[#0F0F0F] rounded p-2 text-xs font-mono text-left">
      <span class="text-[#6E6E6E]">stripe.charges.create()</span>
    </div>
  </div>
  
  <div v-click class="bg-[#171717] border border-[#252525] rounded-lg p-6 text-center">
    <div class="text-4xl mb-4">📱</div>
    <h3 class="text-xl font-bold mb-2">Twilio API</h3>
    <p class="text-sm text-[#6E6E6E] mb-4">Send messages</p>
    <div class="bg-[#0F0F0F] rounded p-2 text-xs font-mono text-left">
      <span class="text-[#6E6E6E]">twilio.messages.create()</span>
    </div>
  </div>
  
  <div v-click class="bg-[#171717] border border-white rounded-lg p-6 text-center">
    <div class="text-4xl mb-4">🧠</div>
    <h3 class="text-xl font-bold mb-2">AI Model API</h3>
    <p class="text-sm text-[#6E6E6E] mb-4">Solve any task</p>
    <div class="bg-[#0F0F0F] rounded p-2 text-xs font-mono text-left">
      <span class="text-[#6E6E6E]">openai.chat.completions()</span>
    </div>
  </div>
</div>

<div v-click class="mt-8 text-center">
  <div class="inline-block bg-[#171717] border border-[#252525] rounded-lg px-6 py-3">
    <span class="text-lg">⚠️ The key difference: <span class="font-bold text-white">No guaranteed identical results</span></span>
  </div>
</div>

---
layout: center
class: px-8
transition: slide-up
---

# AI Hallucinations 🌀

<div class="text-center mb-6">
  <p class="text-[#6E6E6E]">When AI <span class="text-red-400 font-semibold">confidently generates incorrect information</span> that seems plausible</p>
</div>

<div class="grid grid-cols-2 gap-6">
  <div v-click class="bg-[#171717] border border-[#252525] rounded-lg p-5">
    <h3 class="text-lg font-bold mb-4 text-center">🤔 Why does this happen?</h3>
    <ul class="text-sm text-[#6E6E6E] space-y-3">
      <li>AI predicts <span class="text-white">next token based on patterns</span></li>
      <li>Like <span class="text-white">powerful autocomplete</span></li>
      <li>It doesn't say "I don't know" - generates what <span class="text-white">seems most likely</span></li>
    </ul>
  </div>
  
  <div v-click class="bg-[#171717] border border-red-900 rounded-lg p-5">
    <h3 class="text-lg font-bold mb-4 text-center">💻 In coding, this means...</h3>
    <ul class="text-sm text-[#6E6E6E] space-y-2">
      <li>❌ Inventing APIs that don't exist</li>
      <li>❌ Wrong function signatures</li>
      <li>❌ Outdated syntax or methods</li>
      <li>❌ Plausible but buggy logic</li>
    </ul>
  </div>
</div>

<div v-click class="mt-6 text-center">
  <div class="inline-block bg-[#171717] border border-white rounded-lg px-6 py-4">
    <p class="text-sm"><span class="text-green-400 font-bold">✅ The fix:</span> Develop a <span class="text-white font-semibold">verification mindset</span> — every suggestion is a <span class="text-white">starting point</span>, not a final answer</p>
  </div>
</div>

---
layout: center
class: px-8
---

# Understanding Tokens 🧩

<div class="grid grid-cols-2 gap-6 mt-4">
  <div>
    <h3 class="text-lg font-bold mb-3">What is a Token?</h3>
    <div class="bg-[#171717] border border-[#252525] rounded-lg p-3 mb-3">
      <p class="text-xs text-[#6E6E6E] mb-2">A token can be a word or parts of a word:</p>
      <div class="space-y-2">
        <div class="flex items-center gap-2 text-sm">
          <span class="bg-[#0F0F0F] px-2 py-0.5 rounded font-mono text-green-400 text-xs">hello</span>
          <span class="text-[#6E6E6E]">→ 1 token</span>
        </div>
        <div class="flex items-center gap-2 text-sm">
          <span class="bg-[#0F0F0F] px-1 py-0.5 rounded font-mono text-yellow-400 text-xs">un</span>
          <span class="bg-[#0F0F0F] px-1 py-0.5 rounded font-mono text-yellow-400 text-xs">believ</span>
          <span class="bg-[#0F0F0F] px-1 py-0.5 rounded font-mono text-yellow-400 text-xs">able</span>
          <span class="text-[#6E6E6E]">→ 3 tokens</span>
        </div>
      </div>
    </div>
    <div v-click class="bg-[#171717] border border-white rounded-lg p-3">
      <p class="text-xs"><span class="font-bold text-white">💡 Why it matters:</span> <span class="text-[#6E6E6E]">Tokens = <span class="text-white">pricing</span> + <span class="text-white">speed</span></span></p>
    </div>
  </div>
  
  <div>
    <h3 class="text-lg font-bold mb-3">Input vs Output Tokens</h3>
    <div v-click class="space-y-3">
      <div class="bg-[#171717] border border-[#252525] rounded-lg p-3">
        <div class="flex items-center gap-2 mb-1">
          <span class="text-lg">📥</span>
          <span class="font-bold text-white text-sm">Input Tokens</span>
          <span class="text-xs text-green-400 ml-auto">💰 Lower cost</span>
        </div>
        <p class="text-xs text-[#6E6E6E]">Your prompt + context</p>
      </div>
      <div class="bg-[#171717] border border-[#252525] rounded-lg p-3">
        <div class="flex items-center gap-2 mb-1">
          <span class="text-lg">📤</span>
          <span class="font-bold text-white text-sm">Output Tokens</span>
          <span class="text-xs text-red-400 ml-auto">💸 2-4x more!</span>
        </div>
        <p class="text-xs text-[#6E6E6E]">Model's response</p>
      </div>
    </div>
  </div>
</div>

<div v-click class="mt-4 bg-[#171717] border border-[#252525] rounded-lg p-3">
  <p class="text-sm"><span class="font-bold">🌊 Why streaming?</span> <span class="text-[#6E6E6E]">AI generates tokens <span class="text-white">one at a time</span>, predicting the next based on previous ones.</span></p>
</div>

---
layout: center
class: px-8
---

# Context Window 📦



<div class="grid grid-cols-3 gap-4 mb-6">
  <div v-click class="bg-[#171717] border border-[#252525] rounded-lg p-4 text-center">
    <div class="text-3xl mb-2">📝</div>
    <p class="text-sm text-white font-semibold">Your Prompt</p>
    <p class="text-xs text-[#6E6E6E]">What you ask</p>
  </div>
  <div v-click class="bg-[#171717] border border-[#252525] rounded-lg p-4 text-center">
    <div class="text-3xl mb-2">💬</div>
    <p class="text-sm text-white font-semibold">Chat History</p>
    <p class="text-xs text-[#6E6E6E]">Previous messages</p>
  </div>
  <div v-click class="bg-[#171717] border border-[#252525] rounded-lg p-4 text-center">
    <div class="text-3xl mb-2">📂</div>
    <p class="text-sm text-white font-semibold">Code Context</p>
    <p class="text-xs text-[#6E6E6E]">Files & snippets</p>
  </div>
</div>

<div v-click class="bg-[#171717] border border-yellow-600 rounded-lg p-4 mb-4">
  <p class="text-center text-sm"><span class="text-yellow-400 font-bold">⚠️ When context fills up:</span> <span class="text-[#6E6E6E]">AI starts "forgetting" earlier parts → answers get worse</span></p>
</div>

<div v-click class="text-center">
  <div class="inline-block bg-[#171717] border border-green-600 rounded-lg px-6 py-4">
    <p class="text-sm"><span class="text-green-400 font-bold">💡 Mental Model:</span> Watch the context indicator — <span class="text-white font-semibold">when it's filling up, start a new chat</span></p>
  </div>
</div>

---
layout: center
class: px-8
---

# Mental Model Summary 🧠

<div class="grid grid-cols-2 gap-4 mt-4">
  <div v-click class="flex items-center gap-3 bg-[#171717] border border-[#252525] rounded-lg p-3">
    <span class="text-xl">👤</span>
    <div>
      <p class="font-bold text-white text-sm">You are in control</p>
      <p class="text-xs text-[#6E6E6E]">LLMs <span class="text-white">amplify</span> your productivity</p>
    </div>
  </div>

  <div v-click class="flex items-center gap-3 bg-[#171717] border border-[#252525] rounded-lg p-3">
    <span class="text-xl">🎲</span>
    <div>
      <p class="font-bold text-white text-sm">Non-deterministic</p>
      <p class="text-xs text-[#6E6E6E]">Same prompt → <span class="text-white">different responses</span></p>
    </div>
  </div>

  <div v-click class="flex items-center gap-3 bg-[#171717] border border-[#252525] rounded-lg p-3">
    <span class="text-xl">🌀</span>
    <div>
      <p class="font-bold text-white text-sm">LLMs hallucinate</p>
      <p class="text-xs text-[#6E6E6E]">You must <span class="text-white">verify everything</span></p>
    </div>
  </div>

  <div v-click class="flex items-center gap-3 bg-[#171717] border border-[#252525] rounded-lg p-3">
    <span class="text-xl">📦</span>
    <div>
      <p class="font-bold text-white text-sm">Watch context window</p>
      <p class="text-xs text-[#6E6E6E]">New chat at <span class="text-white">~90% filled</span></p>
    </div>
  </div>
</div>

---
layout: section
class: text-center
background: '#171717'
transition: slide-up
---

# Contributing to Open Source with Cursor

<div class="text-4xl font-bold text-white mb-8">🌍</div>

Understanding any codebase in minutes

---
layout: center
class: px-8
transition: slide-up
---

# What is Open Source? 📖

<div class="bg-[#171717] border border-[#252525] rounded-lg p-4 mt-4 mb-6">
  <p class="text-sm text-[#6E6E6E]">Software released under a license where the <span class="text-white font-semibold">copyright holder grants users the right</span> to <span class="text-green-400">use</span>, <span class="text-green-400">study</span>, <span class="text-green-400">change</span>, and <span class="text-green-400">distribute</span> the software and its source code to anyone for any purpose.</p>
</div>

<div class="grid grid-cols-2 gap-6">
  <div v-click>
    <h3 class="text-lg font-bold mb-3">🏗️ Major Projects</h3>
    <div class="flex flex-wrap gap-2">
      <span class="bg-[#0F0F0F] border border-[#252525] px-2 py-1 rounded text-xs">🐧 Linux</span>
      <span class="bg-[#0F0F0F] border border-[#252525] px-2 py-1 rounded text-xs">💻 VS Code</span>
      <span class="bg-[#0F0F0F] border border-[#252525] px-2 py-1 rounded text-xs">⚛️ React</span>
      <span class="bg-[#0F0F0F] border border-[#252525] px-2 py-1 rounded text-xs">🐍 Python</span>
      <span class="bg-[#0F0F0F] border border-[#252525] px-2 py-1 rounded text-xs">☸️ Kubernetes</span>
      <span class="bg-[#0F0F0F] border border-[#252525] px-2 py-1 rounded text-xs">🌐 Chromium</span>
      <span class="bg-[#0F0F0F] border border-[#252525] px-2 py-1 rounded text-xs">🧠 TensorFlow</span>
      <span class="bg-[#0F0F0F] border border-[#252525] px-2 py-1 rounded text-xs">💚 Node.js</span>
      <span class="bg-[#0F0F0F] border border-[#252525] px-2 py-1 rounded text-xs">🦊 Firefox</span>
      <span class="bg-[#0F0F0F] border border-[#252525] px-2 py-1 rounded text-xs">🎨 Blender</span>
      <span class="bg-[#0F0F0F] border border-[#252525] px-2 py-1 rounded text-xs">🔀 Git</span>
      <span class="bg-[#0F0F0F] border border-[#252525] px-2 py-1 rounded text-xs">🐘 PostgreSQL</span>
    </div>
  </div>
  
  <div v-click>
    <h3 class="text-lg font-bold mb-3">🚀 My favourites</h3>
    <div class="flex flex-wrap gap-2">
      <span class="bg-[#0F0F0F] border border-[#252525] px-3 py-1 rounded text-sm">🔗 Dub.co</span>
      <span class="bg-[#0F0F0F] border border-[#252525] px-3 py-1 rounded text-sm">🗺️ Roadmap.sh</span>
      <span class="bg-[#0F0F0F] border border-[#252525] px-3 py-1 rounded text-sm">🎓 freeCodeCamp</span>
      <span class="bg-[#0F0F0F] border border-[#252525] px-3 py-1 rounded text-sm">🛠️ Build Your Own X</span>
    </div>
  </div>
</div>

---
layout: center
class: px-8
transition: slide-up
---

# Why Contribute to Open Source? 🤔

<div v-click class="bg-[#171717] border border-red-900 rounded-lg p-4 mb-6">
  <div class="flex items-center gap-3">
    <span class="text-2xl">⚠️</span>
    <div>
      <p class="text-lg font-bold text-red-400">If you're doing it just to get a job... DON'T.</p>
      <p class="text-sm text-[#6E6E6E] mt-1">Open source requires <span class="text-white font-semibold">patience</span> and <span class="text-white font-semibold">genuine interest</span>.</p>
    </div>
  </div>
</div>

<div v-click>
  <h3 class="text-lg font-bold mb-4 text-green-400">✅ Do it if you want to...</h3>
  <div class="grid grid-cols-5 gap-3">
    <div class="bg-[#171717] border border-[#252525] rounded-lg p-3 text-center">
      <div class="text-2xl mb-2">📈</div>
      <p class="text-xs text-[#6E6E6E]">Improve your <span class="text-white">skills</span></p>
    </div>
    <div class="bg-[#171717] border border-[#252525] rounded-lg p-3 text-center">
      <div class="text-2xl mb-2">🧠</div>
      <p class="text-xs text-[#6E6E6E]">Build a better <span class="text-white">mindset</span></p>
    </div>
    <div class="bg-[#171717] border border-[#252525] rounded-lg p-3 text-center">
      <div class="text-2xl mb-2">🤝</div>
      <p class="text-xs text-[#6E6E6E]">Build <span class="text-white">relationships</span></p>
    </div>
    <div class="bg-[#171717] border border-[#252525] rounded-lg p-3 text-center">
      <div class="text-2xl mb-2">🌍</div>
      <p class="text-xs text-[#6E6E6E]">Have real <span class="text-white">impact</span></p>
    </div>
    <div class="bg-[#171717] border border-[#252525] rounded-lg p-3 text-center">
      <div class="text-2xl mb-2">👁️</div>
      <p class="text-xs text-[#6E6E6E]">Make work <span class="text-white">public</span></p>
    </div>
  </div>
</div>

---
layout: center
class: px-8
transition: slide-up
---

# Where to Find Open Source Projects 🔍

<div class="grid grid-cols-3 gap-4 mt-6">
  <div v-click class="bg-[#171717] border border-[#252525] rounded-lg p-4 text-center hover:bg-[#1F1F1F] transition-colors">
    <div class="text-3xl mb-2">☀️</div>
    <h3 class="text-lg font-bold mb-2 text-white">Google Summer of Code</h3>
    <p class="text-xs text-[#6E6E6E]">Paid summer program for students to contribute to open source</p>
  </div>
  
  <div v-click class="bg-[#171717] border border-[#252525] rounded-lg p-4 text-center hover:bg-[#1F1F1F] transition-colors">
    <div class="text-3xl mb-2">🐧</div>
    <h3 class="text-lg font-bold mb-2 text-white">LFX Mentorship</h3>
    <p class="text-xs text-[#6E6E6E]">Linux Foundation program with stipends for contributors</p>
  </div>
  
  <div v-click class="bg-[#171717] border border-[#252525] rounded-lg p-4 text-center hover:bg-[#1F1F1F] transition-colors">
    <div class="text-3xl mb-2">🎓</div>
    <h3 class="text-lg font-bold mb-2 text-white">MLH Fellowship</h3>
    <p class="text-xs text-[#6E6E6E]">12-week internship alternative with real projects</p>
  </div>
  
  <div v-click class="bg-[#171717] border border-[#252525] rounded-lg p-4 text-center hover:bg-[#1F1F1F] transition-colors">
    <div class="text-3xl mb-2">🪟</div>
    <h3 class="text-lg font-bold mb-2 text-white">Microsoft FOSS Fund</h3>
    <p class="text-xs text-[#6E6E6E]">Microsoft's open source contribution programs</p>
  </div>
  
  <div v-click class="bg-[#171717] border border-[#252525] rounded-lg p-4 text-center hover:bg-[#1F1F1F] transition-colors">
    <div class="text-3xl mb-2">🌈</div>
    <h3 class="text-lg font-bold mb-2 text-white">Outreachy</h3>
    <p class="text-xs text-[#6E6E6E]">Paid internships for underrepresented groups in tech</p>
  </div>
  
  <div v-click class="bg-[#171717] border border-white rounded-lg p-4 text-center hover:bg-[#1F1F1F] transition-colors">
    <div class="text-3xl mb-2">🔥</div>
    <h3 class="text-lg font-bold mb-2 text-white">GitHub Explore</h3>
    <p class="text-xs text-[#6E6E6E]">Find trending repos and good first issues directly</p>
  </div>
</div>

<div v-click class="mt-4 text-center">
  <p class="text-sm text-[#6E6E6E]">💡 Start small, build your portfolio, and grow your network!</p>
</div>

---
layout: center
class: px-8
transition: slide-up
---

# Steps to Your First Contribution 🎯

<div class="grid grid-cols-2 gap-6 mt-8">
  <div v-click class="bg-[#171717] border border-[#252525] rounded-lg p-6">
    <div class="flex items-center gap-3 mb-4">
      <span class="text-3xl">🏷️</span>
      <h3 class="text-xl font-bold">2. Good First Issues</h3>
    </div>
    <ul class="text-sm text-[#6E6E6E] space-y-2">
      <li>Look for <span class="bg-green-900 text-green-300 px-2 py-0.5 rounded text-xs">good first issue</span> labels</li>
      <li>Start small, build confidence</li>
      <li>Ask Cursor to explain the issue context</li>
    </ul>
  </div>
  
  <div v-click class="bg-[#171717] border border-[#252525] rounded-lg p-6">
    <div class="flex items-center gap-3 mb-4">
      <span class="text-3xl">📋</span>
      <h3 class="text-xl font-bold">3. CONTRIBUTING.md</h3>
    </div>
    <ul class="text-sm text-[#6E6E6E] space-y-2">
      <li>Read the contributing guidelines</li>
      <li>Understand code style & conventions</li>
      <li>Check testing requirements</li>
    </ul>
  </div>
  
</div>

---
layout: center
class: px-8
transition: slide-up
---

# 4. Writing Good Pull Requests 📝

<div class="grid grid-cols-3 gap-6 mt-8">
  <div v-click class="bg-[#171717] border border-[#252525] rounded-lg p-6">
    <div class="flex items-center gap-3 mb-4">
      <span class="text-3xl">💬</span>
      <h3 class="text-lg font-bold">Add "Why" Comments</h3>
    </div>
    <p class="text-sm text-[#6E6E6E] mb-4">Don't just explain what the code does — explain <span class="text-white font-semibold">why</span> it does it.</p>
    <div class="bg-[#0F0F0F] rounded-lg p-3 text-xs font-mono">
      <p class="text-[#6E6E6E]">// We use debounce here to</p>
      <p class="text-[#6E6E6E]">// prevent API spam on</p>
      <p class="text-[#6E6E6E]">// rapid keystrokes</p>
    </div>
  </div>
  
  <div v-click class="bg-[#171717] border border-white rounded-lg p-6">
    <div class="flex items-center gap-3 mb-4">
      <span class="text-3xl">📦</span>
      <h3 class="text-lg font-bold">Make PRs Small</h3>
    </div>
    <ul class="text-sm text-[#6E6E6E] space-y-2">
      <li><span class="text-green-400">✓</span> Reviewed more <span class="text-white">quickly</span></li>
      <li><span class="text-green-400">✓</span> Reviewed more <span class="text-white">thoroughly</span></li>
      <li><span class="text-green-400">✓</span> Less <span class="text-white">blocking</span> on reviews</li>
      <li><span class="text-green-400">✓</span> Simpler to <span class="text-white">roll back</span></li>
    </ul>
  </div>
  
  <div v-click class="bg-[#171717] border border-[#252525] rounded-lg p-6">
    <div class="flex items-center gap-3 mb-4">
      <span class="text-3xl">📋</span>
      <h3 class="text-lg font-bold">Clear Description</h3>
    </div>
    <ul class="text-sm text-[#6E6E6E] space-y-2">
      <li><span class="text-white font-semibold">What</span> changed?</li>
      <li><span class="text-white font-semibold">Why</span> this approach?</li>
      <li><span class="text-white font-semibold">How</span> to test it?</li>
      <li>Link to the <span class="text-white font-semibold">issue</span></li>
    </ul>
  </div>
</div>

<div v-click class="mt-6 text-center">
  <div class="inline-block bg-[#171717] border border-[#252525] rounded-lg px-6 py-3">
    <span class="text-sm">💡 A good PR tells a <span class="font-bold text-white">story</span> — reviewers should understand your thinking without asking questions</span>
  </div>
</div>

---
layout: center
class: px-8
transition: slide-up
---

# Common Mistakes to Avoid ⚠️

<div class="grid grid-cols-2 gap-6 mt-8">
  <div v-click class="bg-[#171717] border border-red-900 rounded-lg p-5">
    <div class="flex items-start gap-3">
      <span class="text-2xl">❌</span>
      <div>
        <h3 class="text-lg font-bold text-red-400 mb-2">Blindly Trusting AI Output</h3>
        <p class="text-sm text-[#6E6E6E]">Always review and understand the code AI generates. You're responsible for your commits!</p>
      </div>
    </div>
  </div>
  
  <div v-click class="bg-[#171717] border border-red-900 rounded-lg p-5">
    <div class="flex items-start gap-3">
      <span class="text-2xl">❌</span>
      <div>
        <h3 class="text-lg font-bold text-red-400 mb-2">Large First PRs</h3>
        <p class="text-sm text-[#6E6E6E]">Start small! A 10-line fix is better than a 500-line refactor for your first contribution.</p>
      </div>
    </div>
  </div>
  
  <div v-click class="bg-[#171717] border border-red-900 rounded-lg p-5">
    <div class="flex items-start gap-3">
      <span class="text-2xl">❌</span>
      <div>
        <h3 class="text-lg font-bold text-red-400 mb-2">Ignoring Project Guidelines</h3>
        <p class="text-sm text-[#6E6E6E]">Each project has its own conventions. Read CONTRIBUTING.md and follow the existing patterns.</p>
      </div>
    </div>
  </div>
  
  <div v-click class="bg-[#171717] border border-red-900 rounded-lg p-5">
    <div class="flex items-start gap-3">
      <span class="text-2xl">❌</span>
      <div>
        <h3 class="text-lg font-bold text-red-400 mb-2">Not Understanding Your Change</h3>
        <p class="text-sm text-[#6E6E6E]">If you can't explain what your code does, don't submit it. Take ownership of every line.</p>
      </div>
    </div>
  </div>
</div>

---
layout: center
class: px-8
transition: slide-up
---

# Bonus: Cursor Cloud Agents + Slack 💬

<div class="mt-8 flex justify-center">
  <div class="bg-[#171717] border border-[#252525] rounded-lg p-8 max-w-2xl">
    <div class="flex items-center justify-center gap-4 mb-6">
      <div class="text-5xl">🤖</div>
      <div class="text-4xl">+</div>
      <div class="text-5xl">💬</div>
    </div>
    <h3 class="text-xl font-bold mb-4 text-center">Work on tasks directly from Slack!</h3>
    <div class="bg-[#0F0F0F] rounded-lg p-4 mb-4">
      <p class="text-sm text-[#6E6E6E] mb-2">Example message:</p>
      <p class="font-mono text-green-400">@cursor fix the login bug in auth.ts and open a PR</p>
    </div>
    <p class="text-sm text-[#6E6E6E] text-center">With Cursor's Slack integration, Cloud Agents can work on your tasks by simply mentioning @cursor with a prompt.</p>
  </div>
</div>

---
layout: center
class: text-center px-8
---

# Thank You! 🙏

---
layout: end
class: text-center px-8
---

# Let's Connect 🤝