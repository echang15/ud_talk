---
theme: seriph
background: https://images.unsplash.com/photo-1517245386807-bb43f82c33c4?auto=format&fit=crop&w=1920&q=80
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## The Unwritten Syllabus
  Lecture by Eric Chang
drawings:
  persist: false
transition: slide-left
title: The Unwritten Syllabus
---

# The Unwritten Syllabus

<!--
"In college, you know exactly what to do to get an A. You have a rubric. In your career, there is no rubric. You can do everything 'right' and still fail, or do one thing differently and succeed massively. This talk is about writing your own rubric."
-->

Things they don't teach you in the lecture hall.

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer hover:bg-white hover:bg-opacity-10">
    Press Space to Start <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <a href="https://ericchang.dev" target="_blank" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    Eric Chang, UD 2004. 
  </a>
</div>

---
layout: center
class: text-center
---

# Who is talking and why should I care?

<v-click>

### Eric Chang. Technical Enablement Expert @ Barclays.
UD Alumni. Dad, Husband, Geek. Average College Student.

</v-click>
<v-click>

<div class="grid grid-cols-2 gap-4 mt-8 h-80 w-full">
  <PrivatePhoto src="/private/eric_mirror.jpg" />
  <PrivatePhoto src="/private/eric_ud2.jpg" />
  <PrivatePhoto src="/private/eric_ud3.jpg" />
  <PrivatePhoto src="/private/eric_ud4.jpg" />
</div>
</v-click>

---
layout: center
---

# Agenda

<div class="mt-12 grid grid-cols-2 gap-12 items-center">
  
  <div class="space-y-4">
    <v-click>
      <div class="flex items-center gap-4 p-4 rounded-xl bg-blue-500/10 border border-blue-500/20 hover:bg-blue-500/20 hover:-translate-y-1 transition-all">
        <div class="text-3xl">⏳</div>
        <div class="text-lg font-semibold opacity-90">This will not last 80 minutes</div>
      </div>
    </v-click>
    <v-click>
      <div class="flex items-center gap-4 p-4 rounded-xl bg-green-500/10 border border-green-500/20 hover:bg-green-500/20 hover:-translate-y-1 transition-all">
        <div class="text-3xl">🙋‍♂️</div>
        <div class="text-lg font-semibold opacity-90">I am interactive. Ask questions!</div>
      </div>
    </v-click>
    <v-click>
      <div class="flex items-center gap-4 p-4 rounded-xl bg-purple-500/10 border border-purple-500/20 hover:bg-purple-500/20 hover:-translate-y-1 transition-all">
        <div class="text-3xl">🗺️</div>
        <div class="text-lg font-semibold opacity-90">How I got here</div>
      </div>
    </v-click>
    <v-click>
      <div class="flex items-center gap-4 p-4 rounded-xl bg-yellow-500/10 border border-yellow-500/20 hover:bg-yellow-500/20 hover:-translate-y-1 transition-all">
        <div class="text-3xl">💡</div>
        <div class="text-lg font-semibold opacity-90">Lessons learned</div>
      </div>
    </v-click>
  </div>

  <div class="flex flex-col items-center justify-center">
    <div class="relative group mt-4">
      <div class="absolute -inset-1 bg-gradient-to-r from-teal-500 to-blue-500 rounded-2xl blur opacity-25 group-hover:opacity-75 transition duration-1000 group-hover:duration-200"></div>
      <div class="relative w-40 h-40 p-3 bg-white rounded-xl shadow-2xl flex items-center justify-center transform hover:scale-105 transition-all">
        <PrivatePhoto src="/private/qr_code.jpg" />
      </div>
      <div class="absolute -bottom-8 left-0 right-0 text-center text-sm font-bold opacity-60 uppercase tracking-widest text-teal-400">
        Follow Along
      </div>
    </div>
  </div>

</div>

---
layout: two-cols
---

# College Life (2000 - 2004)

<div class="grid grid-cols-2 grid-rows-2 gap-3 mt-4 h-[420px] w-full">
  <div class="h-full">
    <PrivatePhoto src="/private/eric_college1.jpg">
      <div class="h-full flex items-center justify-center bg-gray-100 dark:bg-gray-800 rounded-lg">
        <div class="text-4xl opacity-20">
          <carbon:image />
          <span class="block text-sm mt-2">Photo Placeholder</span>
        </div>
      </div>
    </PrivatePhoto>
  </div>
  <div class="h-full">
    <PrivatePhoto src="/private/eric_college2.jpg" />
  </div>
  <div class="h-full">
    <PrivatePhoto src="/private/eric_college3.jpg" />
  </div>
  <div class="h-full">
    <PrivatePhoto src="/private/eric_college4.jpg" />
  </div>
</div>

::right::

<div class="ml-4 space-y-4">

<v-click>
  <div class="p-4 border-l-4 border-blue-500 bg-blue-500/10">
    <h3 class="text-lg font-bold">Key Accomplishments</h3>
    <ul class="list-disc pl-4 text-sm opacity-80">
      <li>Sponsored Video Gamer - 50 bucks a month!</li>
      <li>Barely passed Discrete Math</li>
      <li>Threw a printer from 3rd floor of Cannon Hall</li>
      <li>Slept Thru Graduation</li>
    </ul>
  </div>
</v-click>  

<v-click>
  <div class="p-4 border-l-4 border-green-500 bg-green-500/10">
    <h3 class="text-lg font-bold">Key Lessons Learned</h3>
    <ul class="list-disc pl-4 text-sm opacity-80">
      <li>Hard work beats raw talent.</li>
      <li>Habits (Good or Bad) Compound.</li>
      <li>You can reinvent yourself.</li>
      <li>Nobody wins at Jager-Pong</li>
    </ul>
  </div>
</v-click>

</div>

---
layout: two-cols
---

# Top Line Express (2004-2006)

<!--
"I didn't start at Google or Facebook. I started in logistics. It taught me that tech isn't just about code; it's about solving business problems. If the trucks don't move, nobody gets paid. That pressure taught me more than any coding bootcamp."
-->

<div class="grid grid-cols-2 grid-rows-2 gap-3 mt-4 h-[420px] w-full">
  <div class="h-full">
    <PrivatePhoto src="/private/top_line.jpg">
      <div class="h-full flex items-center justify-center bg-gray-100 dark:bg-gray-800 rounded-lg">
        <div class="text-4xl opacity-20">
          <carbon:delivery-truck />
          <span class="block text-sm mt-2">Top Line Express Photo</span>
        </div>
      </div>
    </PrivatePhoto>
  </div>
  <div class="h-full">
    <PrivatePhoto src="/private/eric_topline2.jpg" />
  </div>
  <div class="h-full">
    <PrivatePhoto src="/private/eric_topline3.jpg" />
  </div>
  <div class="h-full">
    <PrivatePhoto src="/private/eric_topline4.jpg" />
  </div>
</div>

::right::

<div class="ml-4 space-y-4">

<v-click>
  <div class="p-4 border-l-4 border-blue-500 bg-blue-500/10">
    <h3 class="text-lg font-bold">Key Accomplishments</h3>
    <ul class="list-disc pl-4 text-sm opacity-80">
      <li>First "Real" Job</li>
      <li>Learned the value of a dollar</li>
      <li>Transformed entire IT Infrastructure.</li>
      <li>Learned a little about everything</li>
    </ul>
  </div>
</v-click>

<v-click>
  <div class="p-4 border-l-4 border-green-500 bg-green-500/10">
    <h3 class="text-lg font-bold">Key Lessons Learned</h3>
    <ul class="list-disc pl-4 text-sm opacity-80">
      <li>What i DIDNT want to spend the rest of my life doing.</li>
      <li>Micromanagement is a disease.</li>
      <li>When Everything is Top Urgent, Nothing is Top Urgent.</li>
    </ul>
  </div>
</v-click>

</div>

---
layout: two-cols
---

# JPMorganChase (2006-2023)

<!--
"Spending 17 years at one place is rare now. Why did I stay? Because I could reinvent myself every 2-3 years without leaving the building. Intrapreneurship is a safe way to be an entrepreneur."
-->

<div class="grid grid-cols-2 grid-rows-2 gap-3 mt-4 h-[420px] w-full">
  <div class="h-full">
    <PrivatePhoto src="/private/eric_patents.jpg">
      <div class="h-full flex items-center justify-center bg-gray-100 dark:bg-gray-800 rounded-lg">
        <div class="text-4xl opacity-20">
          <carbon:building />
          <span class="block text-sm mt-2">JPMC Office Photo</span>
        </div>
      </div>
    </PrivatePhoto>
  </div>
  <div class="h-full">
    <PrivatePhoto src="/private/eric_leap.jpg" />
  </div>
  <div class="h-full">
    <PrivatePhoto src="/private/eric_cfg.jpg" />
  </div>
  <div class="h-full">
    <PrivatePhoto src="/private/eric_inventor.jpg" />
  </div>
</div>

::right::

<div class="ml-4 space-y-4">

<v-click>
  <div class="p-4 border-l-4 border-blue-500 bg-blue-500/10">
    <h3 class="text-lg font-bold">Key Accomplishments</h3>
    <ul class="list-disc pl-4 text-sm opacity-80">
      <li>20+ Patent Filings</li>
      <li>Expert Engineer / Prolific Inventor</li>
      <li>Ran Billion Dollar+ Infrastructure Programs</li>
      <li>New Hire Orientation</li>
      <li>Leadership Engineering Advancement Program</li>
    </ul>
  </div>
</v-click>

<v-click>
  <div class="p-4 border-l-4 border-green-500 bg-green-500/10">
    <h3 class="text-lg font-bold">Key Lessons Learned</h3>
    <ul class="list-disc pl-4 text-sm opacity-80">
      <li>You are the manager of your own career.</li>
      <li>Be the Doctor, not the Waiter.</li>
      <li>Networking pays off</li>
      <li>Get involved - Give Back</li>
    </ul>
  </div>
</v-click>
</div>

---
layout: two-cols
---

# Barclays (2023-Present)

<div class="grid grid-cols-2 grid-rows-2 gap-3 mt-4 h-[420px] w-full">
  <div class="h-full">
    <PrivatePhoto src="/private/eric_india.jpg">
      <div class="h-full flex items-center justify-center bg-gray-100 dark:bg-gray-800 rounded-lg">
        <div class="text-4xl opacity-20">
          <carbon:building-insights-3 />
          <span class="block text-sm mt-2">Barclays Photo</span>
        </div>
      </div>
    </PrivatePhoto>
  </div>
  <div class="h-full">
    <PrivatePhoto src="/private/eric_ai_talk.jpg" />
  </div>
  <div class="h-full">
    <PrivatePhoto src="/private/eric_craig.jpg" />
  </div>
  <div class="h-full">
    <PrivatePhoto src="/private/eric_mod1.jpg" />
  </div>
</div>

::right::

<div class="ml-4 space-y-4">

<v-click>
  <div class="p-4 border-l-4 border-blue-500 bg-blue-500/10">
    <h3 class="text-lg font-bold">Key Accomplishments</h3>
    <ul class="list-disc pl-4 text-sm opacity-80">
      <li>Run Global Expert Engineer Programme</li>
      <li>Lead Technical Enablement Workshops</li>
      <li>Drive Engineering Modernisation</li>
      <li>Drive AI Adoption for 20k+ Engineers</li>
    </ul>
  </div>
</v-click>

<v-click> 
  <div class="p-4 border-l-4 border-green-500 bg-green-500/10">
    <h3 class="text-lg font-bold">Key Lessons Learned</h3>
    <ul class="list-disc pl-4 text-sm opacity-80">
      <li>English and <i>The Queen's English</i> are not the same.</li>
      <li>Be the Change you want to see.</li>
      <li>Ask for help.</li>
      <li>Ask "Why?"</li>
    </ul>
  </div>
</v-click>
</div>

---
layout: center
class: text-center
---

# Why the heck am I here?

<v-click>

### Because I wish someone told me what I'm about to tell you.

</v-click>

<v-click>

<div class="mt-8 text-xl opacity-80">
  I made every mistake in the book so you don't have to. Plus I ran into Heather after 20 years.
</div>

</v-click>

---
layout: center
class: text-center
---

# The University Lie (Sorry Heather)

<v-click>

## "Once I graduate, I'll be ready."

</v-click>

<div class="mt-8 grid grid-cols-1 justify-center">
  <div v-click class="text-xl opacity-80">
    The syllabus ends. The learning doesn't.
  </div>
</div>

---

# Lesson 1: Static vs Growth Mindset

<!--
"Many of you were the smartest kids in your high school. You got here and realized everyone else is too. That identity—'I'm smart'—is fragile. If you struggle, you think 'I'm not smart anymore.' Change your identity to 'I'm a hard worker' or 'I'm a learner.' That is anti-fragile."
-->

### "I'm not good at this" vs "I'm not good at this *YET*"

<div class="grid grid-cols-2 gap-4 mt-8">

<v-click>

<div class="p-4 border-l-4 border-red-500 bg-red-500/10">
  <h3 class="text-lg font-bold">Static Mindset</h3>
  <ul class="list-disc pl-4 text-sm opacity-80 space-y-2 mt-2">
    <li>"I'll look dumb if I ask."</li>
    <li>"Feedback is a personal attack."</li>
    <li>"I stick to what I know."</li>
  </ul>
</div>

</v-click>

<v-click>

<div class="p-4 border-l-4 border-green-500 bg-green-500/10">
  <h3 class="text-lg font-bold">Growth Mindset</h3>
  <ul class="list-disc pl-4 text-sm opacity-80 space-y-2 mt-2">
    <li>"Asking questions makes me smarter."</li>
    <li>"Feedback is how I improve."</li>
    <li>"Challenges help me grow."</li>
  </ul>
</div>

</v-click>

</div>

<v-click>

<div class="mt-12 text-center">
  <p class="text-xl font-light italic">
 Everybody sucks at everything when they first try.
  </p>
  <p class="text-sm opacity-50 mt-2">— Eric Chang (Probably)</p>
</div>

</v-click>

---
layout: two-cols
---

# Lesson 2: Extra Credit

### The "1% Rule" is real life extra credit.

<v-click>

<div class="mt-8">
  <div class="text-xl font-bold text-green-500 mb-2">The Compound Effect</div>
  <p class="opacity-80">
    You don't get a grade at the end of the semester. <br>
    You get a reputation at the end of the year.
  </p>
</div>

</v-click>

<v-click>

<div class="mt-8 p-4 bg-gray-100 dark:bg-gray-800 rounded-xl border-l-4 border-blue-500">
  <h3 class="!m-0 text-lg">Consistency &gt; All-Nighters</h3>
  <p class="text-sm mt-2 opacity-75">
    Cramming works for exams. It fails for careers.<br>
    Doing one small thing every day beats doing one big thing once a month.
  </p>
</div>

</v-click>

::right::

<div class="flex h-full items-center justify-center p-4">
  <div class="w-full bg-white p-4 rounded text-black">
    <div class="text-center font-bold mb-4">The Career Curve</div>
    <div class="relative w-full h-64 border-l-2 border-b-2 border-gray-800">
       <div class="absolute bottom-0 left-0 w-full h-full" style="clip-path: polygon(0 100%, 100% 40%, 100% 100%); background: rgba(150, 150, 150, 0.2);"></div>
       <div class="absolute bottom-20 right-2 text-xs text-gray-500">Raw Talent</div>
       <div class="absolute bottom-0 left-0 w-full h-full" style="clip-path: polygon(0 100%, 30% 95%, 60% 80%, 80% 50%, 100% 0, 100% 100%); background: rgba(34, 197, 94, 0.4);"></div>
       <div class="absolute top-0 right-2 text-xs text-green-600 font-bold">Consistency</div>
    </div>
  </div>
</div>

---
layout: image-left
image: https://images.unsplash.com/photo-1516035069371-29a1b244cc32?auto=format&fit=crop&w=800&q=80
---

# Lesson 3: Embracing Failure

### "It's not an F. It's a Bug Report."

<v-click>

<div class="mt-8 space-y-6">

  <div class="p-4 bg-red-500/10 border-l-4 border-red-500 rounded-r">
    <h3 class="text-lg font-bold !m-0">The Academic Fear</h3>
    <p class="opacity-75 text-sm">One bad grade ruins the GPA. Mistakes are permanent.</p>
  </div>

  <div class="p-4 bg-blue-500/10 border-l-4 border-blue-500 rounded-r">
    <h3 class="text-lg font-bold !m-0">Embracing Failure</h3>
    <p class="opacity-75 text-sm">Code never works the first time. Errors tell you what to fix.<br>You are constantly in beta - Use a feedback loop</p>
  </div>

</div>

</v-click>

---

# Lesson 4: The Multiplayer Multiplier

<!--
"Don't network when you need a job. That's asking for a favor. Network when you *don't* need anything. That's building a relationship."
Challenge: Send 5 LinkedIn connection requests to alumni from this university *today*. Don't ask for a job. Just say, 'I'm a student at UD, I saw you're doing great things at X, and I'd love to follow your journey.'
-->

### Focusing only on your GPA is playing Single Player.

<div class="mt-8 grid grid-cols-2 gap-8">
  <div class="opacity-80">
    <h3 class="font-bold mb-2">Solo Queue (The Student)</h3>
    <ul class="list-disc pl-4 space-y-2">
      <li>Heads down</li>
      <li>Competing with classmates</li>
      <li>"I can do it myself"</li>
    </ul>
  </div>
  <div class="text-green-500">
    <h3 class="font-bold mb-2">Full Squad (The Professional)</h3>
    <ul class="list-disc pl-4 space-y-2">
      <li>Heads up</li>
      <li>Collaborating with peers</li>
      <li>"Who can help me solve this?"</li>
    </ul>
  </div>
</div>

<v-click>

<div class="mt-12 p-6 bg-gray-100 dark:bg-gray-800 rounded-xl border-l-4 border-purple-500 text-center">
  <h2 class="text-2xl font-bold mb-4">The Unfair Advantage</h2>
  <p class="text-lg italic opacity-80">
    A strong squad turns hard mode into easy mode. Opportunities find you when you are visible to the right players.
  </p>
  <p class="mt-4 text-sm font-bold uppercase tracking-widest text-purple-400">Building a strong team IS Networking - your reputation builds opportunities.</p>
</div>

</v-click>

---

# Lesson 5: Learning How to Learn

<!--
"The framework you learn today will be legacy code in 3 years. Don't marry the tool; marry the problem-solving process."
"AI is like an Iron Man suit. If you're weak, it'll crush you. If you're strong/skilled, it makes you a superhero. Learn the fundamentals so you can direct the AI."
-->

### The only skill that is recession-proof.

<v-click>

<div class="mt-8 p-6 border-l-4 border-red-500 bg-red-500/10">
  <h3 class="text-xl font-bold mb-2">The Cold Hard Truth</h3>
  <p class="text-lg opacity-90">
    "I use 0% of the tech I learned in college today."
  </p>
</div>

</v-click>

<div class="mt-8 grid grid-cols-2 gap-8">

<v-click>

  <div class="p-4 bg-gray-100 dark:bg-gray-800 rounded-lg">
    <h3 class="font-bold mb-2">The Syntax Changes</h3>
    <ul class="list-disc pl-4 text-sm opacity-75 space-y-1">
    <li>Don't get to attached to the tools you use.</li>
      <li>C -> C++ -> Java</li>
      <li>JavaScript ->jQuery -> React</li>
      <li>Servers -> Containers -> Cloud</li>
    </ul>
  </div>

</v-click>

<v-click>

  <div class="p-4 bg-gray-100 dark:bg-gray-800 rounded-lg">
    <h3 class="font-bold mb-2">The Learning Approach Remains</h3>
    <ul class="list-disc pl-4 text-sm opacity-75 space-y-1">
      <li>Stop Watching and Start Doing</li>
      <li>Consistency > Intensity</li>
      <li>Build Muscle Memory</li>
      <li>Don't try to boil the ocean</li>
      <li>Intentional Practice is key</li>
    </ul>
  </div>

</v-click>

</div>

<v-click>

<div class="mt-8 text-center">
  <p class="text-xl font-bold bg-clip-text text-transparent bg-gradient-to-r from-blue-500 to-green-500">
    Your degree only proves you've commited to something long enough to see it through.
  </p>
</div>

</v-click>

---

# Lesson 6: Be the Dumbest in the Room

### If you are the smartest person in the room, you are in the wrong room.

<v-click>

<div class="mt-8 grid grid-cols-2 gap-8">

  <div class="p-6 bg-red-500/10 border-l-4 border-red-500">
    <h3 class="font-bold text-lg mb-2">The Ego Trap</h3>
    <p class="opacity-80">
      Feeling smart feels safe. But comfort is where growth dies.
    </p>
  </div>

  <div class="p-6 bg-green-500/10 border-l-4 border-green-500">
    <h3 class="font-bold text-lg mb-2">The Growth Hack</h3>
    <p class="opacity-80">
      Osmosis is real. Surround yourself with people who intimidate you intellectually.
    </p>
  </div>

</div>

</v-click>

<v-click>

<div class="mt-12 text-center max-w-2xl mx-auto">
  <p class="text-xl font-light italic">
    "Always be the worst guy in every band you're in. If you're the best guy there, you need to be in a different band."
  </p>
  <p class="text-sm opacity-50 mt-2">— Pat Metheny</p>
</div>

</v-click>

---
layout: center
class: text-center
---

# The Luck Formula

<v-click>

### "Luck is truly where preparation meets opportunity."
<div class="opacity-75 text-sm mt-2">— Randy Pausch, *The Last Lecture*</div>

</v-click>

<v-click>

<div class="mt-12 flex items-center justify-center gap-8 text-2xl font-bold">
  <div class="text-blue-500 text-center">
    Preparation<br>
    <span class="text-base opacity-50 font-normal">(Skills + Habits)</span>
  </div>
  <div>+</div>
  <div class="text-green-500 text-center">
    Opportunity<br>
    <span class="text-base opacity-50 font-normal">(Access + Networking)</span>
  </div>
  <div>=</div>
  <div class="text-yellow-500">Luck 🍀</div>
</div>

</v-click>

<v-click>

<div class="mt-12 p-4 bg-yellow-500/10 border-l-4 border-yellow-500 text-left mx-auto max-w-2xl">
  <p class="opacity-90">
    You can't control the random opportunity. But you can control the preparation so you're ready when it arrives.
  </p>
</div>

</v-click>

---
layout: center
class: text-center text-white
background: https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=1920&q=80
---

# TRUTH BOMBS

<div class="text-left mt-10 space-y-4 text-xl backdrop-blur-md bg-black/50 p-8 rounded-xl">
  <v-click>🛑 No one cares about your grades. Skills get you the job. <br /></v-click>
  <v-click>🛑 No one is coming to save you. Be your own advocate.<br /></v-click>
  <v-click>🛑 Introverts - You're doing this on Hard Mode.<br /></v-click>
  <v-click>🛑 Get Comfortable getting Uncomfortable. (Professionally)<br /></v-click>
  <v-click>🛑 The climb up the "Mountain" is never a straight line.<br /></v-click>
</div>

<!--
Use AI as a tutor, not a cheater. Let it explain concepts, generate test cases, or refactor code. But always understand the output.
-->

---
layout: center
class: text-center
---

# System Maintenance

<!--
"We glorify 'crunch mode' in tech. But if a server runs at 100% CPU for a week, it crashes. Humans are the same. Sleep and downtime are not 'time off,' they are 'system updates'."
-->

<div class="bg-black/60 backdrop-blur-sm p-8 rounded-xl mt-8 text-white">

<v-click>

### You cannot run at 100% CPU usage forever.

</v-click>

<v-click>

<div class="text-xl mt-6 font-light">
  Burnout is not a badge of honor. It's a system failure.
</div>

</v-click>

<v-click>

<div class="grid grid-cols-2 gap-8 mt-12 text-left">
  <div class="border-l-2 border-red-500 pl-4">
    <span class="text-gray-300 text-sm uppercase tracking-widest">The Glitch</span>
    <p class="text-lg">Ignoring mental health to "grind" harder.</p>
  </div>
  <div class="border-l-2 border-green-500 pl-4">
    <span class="text-gray-300 text-sm uppercase tracking-widest">The Patch</span>
    <p class="text-lg">Mental Health is Health.</p>
  </div>
</div>

</v-click>

</div>

---

# 3 Things to Put in Your Backpack

<div class="grid grid-cols-3 gap-4 mt-12 text-center">

<v-click>
  <div class="p-4 bg-blue-500/10 rounded-xl">
    <div class="text-4xl mb-4">🔍</div>
    <h3 class="text-lg font-bold">Curiosity</h3>
    <p class="text-sm opacity-75">Treat everything like a puzzle, not a task. Ask "Why?" more than "How?"</p>
  </div>
</v-click>

<v-click>
  <div class="p-4 bg-purple-500/10 rounded-xl">
    <div class="text-4xl mb-4">🔁</div>
    <h3 class="text-lg font-bold">Iteration</h3>
    <p class="text-sm opacity-75">You don't have to be perfect. You just have to be better than yesterday.</p>
  </div>
</v-click>

<v-click>
  <div class="p-4 bg-orange-500/10 rounded-xl">
    <div class="text-4xl mb-4">🤝</div>
    <h3 class="text-lg font-bold">Connection</h3>
    <p class="text-sm opacity-75">Build your squad. Dig the well before you're thirsty.</p>
  </div>
</v-click>

</div>

---

# The Art of the Presentation - Bonus Material

<div class="space-y-3 mt-6 text-sm">
  <v-click>
  <div class="flex items-center gap-4 p-3 border-l-4 border-blue-500 bg-blue-500/10 rounded-r">
    <div class="w-32 flex-shrink-0">
      <div class="font-bold text-lg text-blue-500">Context</div>
      <div class="text-[10px] opacity-75 uppercase tracking-wide">Problem Statement</div>
    </div>
    <div class="opacity-90 leading-tight">
      Don't assume they remember why you're there. Define the "pain" or "opportunity" in one sentence. If there is no clear problem, there is no reason for the meeting.
    </div>
  </div>
  </v-click>
  
  <v-click>
  <div class="flex items-center gap-4 p-3 border-l-4 border-purple-500 bg-purple-500/10 rounded-r">
    <div class="w-32 flex-shrink-0">
      <div class="font-bold text-lg text-purple-500">Outcome</div>
      <div class="text-[10px] opacity-75 uppercase tracking-wide">The Three I's</div>
    </div>
    <div class="opacity-90 leading-tight">
      Choose one primary goal: Inspire (vision), Influence (buy-in/decisions), or Inform (status updates). Be explicit about what you want them to do after the last slide.
    </div>
  </div>
  </v-click>

  <v-click>
  <div class="flex items-center gap-4 p-3 border-l-4 border-green-500 bg-green-500/10 rounded-r">
    <div class="w-32 flex-shrink-0">
      <div class="font-bold text-lg text-green-500">Audience</div>
      <div class="text-[10px] opacity-75 uppercase tracking-wide">Empathy & Prep</div>
    </div>
    <div class="opacity-90 text-xs leading-tight">
      <span class="font-bold text-green-500/80">Who:</span> Are they technical or business-focused? What do they care about?
      <span class="font-bold text-green-500/80 ml-2">Knowledge:</span> Meet them where they are; avoid jargon.<br>
      <span class="font-bold text-green-500/80">Preference:</span> Do they like to interrupt with questions or wait until the end?
    </div>
  </div>
  </v-click>

  <v-click>
  <div class="flex items-center gap-4 p-3 border-l-4 border-yellow-500 bg-yellow-500/10 rounded-r">
    <div class="w-32 flex-shrink-0">
      <div class="font-bold text-lg text-yellow-500">Medium</div>
      <div class="text-[10px] opacity-75 uppercase tracking-wide">Environment</div>
    </div>
    <div class="opacity-90 text-xs leading-tight">
      <span class="font-bold text-yellow-500/80">Virtual:</span> Look at the camera lens, not the screen, to simulate eye contact.<br>
      <span class="font-bold text-yellow-500/80">In-Person:</span> Use the room; move away from the podium to build trust.
    </div>
  </div>
  </v-click>

  <v-click>
  <div class="flex items-center gap-4 p-3 border-l-4 border-red-500 bg-red-500/10 rounded-r">
    <div class="w-32 flex-shrink-0">
      <div class="font-bold text-lg text-red-500">Delivery</div>
      <div class="text-[10px] opacity-75 uppercase tracking-wide">Ticks & Practice</div>
    </div>
    <div class="opacity-90 text-xs leading-tight">
      <span class="font-bold text-red-500/80">Ticks:</span> Identify your "filler" words (um, like, right). Power of the Pause—silence is better than a verbal tick and projects confidence.<br>
      <span class="font-bold text-red-500/80">Practice:</span> You perform like you practice. Get feedback from peers you trust. Don't just read the slides.
    </div>
  </div>
  </v-click>
</div>

---
layout: center
class: text-center
---

# A presentation about nothing...

<div class="mt-8 flex justify-center w-full max-w-4xl mx-auto h-[450px]">
  <PrivateVideo src="/private/ted_talk.mp4" />
</div>

---
layout: center
class: text-center
---

# On being the Dumbest one in the room...

<div class="mt-8 flex justify-center w-full max-w-4xl mx-auto h-[450px]">
  <PrivateVideo src="/private/simon_sinek.mp4" />
</div>

---
layout: center
class: text-center
---

# Q&A

<h3 class="opacity-80">Office Hours are Open.</h3>

<div class="mt-16 flex items-center justify-center gap-16">
  
  <div class="relative group">
    <div class="absolute -inset-1 bg-gradient-to-r from-blue-500 to-purple-500 rounded-2xl blur opacity-25 group-hover:opacity-75 transition duration-1000 group-hover:duration-200"></div>
    <div class="relative w-48 h-48 p-4 bg-white rounded-xl shadow-2xl flex items-center justify-center transform hover:scale-105 transition-all">
      <PrivatePhoto src="/private/qr_linkedin.jpg" />
    </div>
    <div class="absolute -bottom-8 left-0 right-0 text-center text-sm font-bold opacity-50 uppercase tracking-widest">
      Scan to Connect
    </div>
  </div>

  <div class="flex flex-col gap-6 text-left w-96">
          <div class="flex items-center gap-4 p-4 rounded-xl bg-blue-500/10 border border-blue-500/20 hover:-translate-y-1 transition-all">
      <div class="text-4xl"><carbon:logo-linkedin class="text-4xl text-blue-500" /></div>
      <div>
        <div class="font-bold text-lg text-red-400"></div>
        <div class="text-sm opacity-75">linkedin.com/in/echang15</div>
      </div>
    </div>
    <div class="flex items-center gap-4 p-4 rounded-xl bg-red-500/10 border border-red-500/20 hover:-translate-y-1 transition-all">
      <div class="text-4xl">📵</div>
      <div>
        <div class="font-bold text-lg text-red-400">Pro Tip</div>
        <div class="text-sm opacity-75">Uninstall your socials - seriously!</div>
      </div>
    </div>
  </div>

</div>