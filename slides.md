---
theme: default
title: Planning to Teach
colorSchema: light
css: unocss
transition: fade
mdc: false
---

<div class="dark-bg" style="position:absolute;inset:0;overflow:hidden;">
  <div style="position:absolute;top:-90px;right:-60px;width:340px;height:340px;border-radius:999px;background:var(--navy2);"></div>
  <div style="position:absolute;bottom:-120px;left:-100px;width:260px;height:260px;border-radius:999px;background:var(--navy2);"></div>
</div>

<div style="position:relative;padding:2.4em 3em;height:100%;display:flex;flex-direction:column;justify-content:center;">
  <div class="icon-circle" style="width:64px;height:64px;background:var(--gold);margin-bottom:1.2em;">
    <Icon name="clipboardList" :size="30" color="#1B2A4A" />
  </div>
  <div class="kicker" style="font-size:13px;">Early-Service Teacher Planning Series</div>
  <h1 style="font-size:52px;color:#fff;margin:0.1em 0;">Planning to Teach</h1>
  <div style="font-size:19px;color:var(--cream);margin-bottom:0.6em;">Daily Lesson Design, Cognitive Rigor, and Standards Alignment</div>
  <div style="width:80px;height:2px;background:var(--gold);margin:0.6em 0;"></div>
  <div style="font-size:13px;font-style:italic;color:#C7CEDC;max-width:640px;line-height:1.5;">
    A review of planning practices for teachers new to the district — grounded in Madeline Hunter's lesson design,
    Bloom's Taxonomy, Webb's Depth of Knowledge, and state content standards.
  </div>
  <div style="font-size:11px;color:#8C9AC0;margin-top:1.4em;">Education Services &nbsp;•&nbsp; New Teacher Orientation</div>
</div>

<!--
Welcome. This session is about one of the most consequential habits a new teacher builds: the daily plan. We'll walk
through four frameworks that, together, make a daily plan rigorous and standards-aligned — Madeline Hunter's model of
lesson design, Bloom's Taxonomy, Webb's Depth of Knowledge, and your state content standards. But the real destination
isn't any single lesson. It's what happens when you save every plan you write: that stack of daily plans becomes the
raw material for your unit maps, your semester pacing, and eventually your whole year-to-year program. Let's start
with why this habit matters so much in your first year.
-->

---

<div class="kicker">Setting the Stage</div>
<h1 class="slide-title">Why Daily Planning Matters Most in Year One</h1>
<p class="lede">Planning research consistently finds that novice and experienced teachers plan differently — and that the difference is a skill gap, not a personality trait.</p>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1.2em;">
  <div style="display:flex;flex-direction:column;gap:0.7em;">
    <div class="card panel">
      <div style="font-weight:700;color:var(--navy);font-size:14px;">Novice planning is visible and linear</div>
      <div style="color:var(--muted);font-size:12.5px;margin-top:0.3em;">New teachers rely on detailed, step-by-step written plans and think largely in the short term — the next activity, the next transition, the next 10 minutes.</div>
    </div>
    <div class="card">
      <div style="font-weight:700;color:var(--navy);font-size:14px;">Expert planning becomes internalized</div>
      <div style="color:var(--muted);font-size:12.5px;margin-top:0.3em;">With experience, planning shifts toward long-range, flexible, mental routines; the written plan becomes a lighter scaffold rather than a script.</div>
    </div>
    <div class="card panel">
      <div style="font-weight:700;color:var(--navy);font-size:14px;">The gap closes through deliberate practice</div>
      <div style="color:var(--muted);font-size:12.5px;margin-top:0.3em;">Writing out full, standards-anchored daily plans — repeatedly — is what builds the pattern recognition experienced teachers rely on.</div>
    </div>
  </div>

  <div class="card navy" style="display:flex;flex-direction:column;gap:0.7em;">
    <div class="icon-circle" style="background:var(--rust);"><Icon name="triangleAlert" :size="20" color="#fff" /></div>
    <div style="font-family:Cambria,Georgia,serif;font-weight:700;font-size:17px;">The Research Signal</div>
    <div style="font-style:italic;color:var(--cream);font-size:13px;line-height:1.5;">"For some novice teachers, lesson planning is a source of anxiety… planning lessons is difficult to learn."</div>
    <div style="font-size:10.5px;color:#9FB0CE;">— John (2006), on beginning teachers' experience of planning</div>
    <div style="border-top:1px solid var(--navy2);margin:0.3em 0;"></div>
    <div style="font-weight:700;color:var(--gold);font-size:12.5px;">What this means for you</div>
    <ul class="bullet-list" style="color:#fff;">
      <li>Detailed daily plans aren't a crutch — they're the deliberate practice that builds expert judgment.</li>
      <li>A consistent planning routine, repeated daily, compounds into instructional fluency by year two or three.</li>
      <li>Every plan you write and keep is an asset — not a one-time artifact for a single class period.</li>
    </ul>
  </div>
</div>

<div class="footer-bar"><span>Planning to Teach — Early-Service Teacher Series</span><span>2</span></div>

<!--
Let's start with the research, because it reframes what daily planning is for. Studies comparing novice and experienced
teachers find a consistent pattern: new teachers plan in a visible, linear, step-by-step way, focused on the next few
minutes of class, while experienced teachers plan in longer arcs and hold much of it in their heads. That's not a
talent gap — John's 2006 review in the Journal of Curriculum Studies found this is a developmental stage almost every
teacher passes through. The skill of planning is learned through repetition. So when we ask you to write detailed
daily plans in your first year or two, we're not asking you to do something a veteran teacher doesn't do — we're
asking you to do consciously and on paper what they now do automatically. Every plan you write is deliberate
practice, and it's also something you'll be able to reuse.
-->

---

<div class="kicker">Roadmap</div>
<h1 class="slide-title">Four Frameworks Behind Every Strong Daily Plan</h1>
<p class="lede">Each framework answers a different planning question. Together, they turn a single day's lesson into something rigorous, purposeful, and traceable back to what students are legally entitled to learn.</p>

<div style="display:grid;grid-template-columns:repeat(4,1fr);gap:0.8em;">
  <div class="card" style="padding:0;overflow:hidden;">
    <div style="background:var(--navy);padding:1.1em 0;display:flex;align-items:center;justify-content:center;">
      <div class="icon-circle" style="width:52px;height:52px;background:rgba(255,255,255,0.15);border:2px solid rgba(255,255,255,0.6);"><Icon name="clipboardList" :size="24" color="#fff" /></div>
    </div>
    <div style="padding:0.9em;">
      <div class="badge" style="color:var(--navy);">Structure</div>
      <div style="font-family:Cambria,Georgia,serif;font-weight:700;font-size:15px;color:var(--navy);margin:0.2em 0;">Madeline Hunter</div>
      <div style="font-style:italic;font-weight:700;font-size:11px;color:var(--navy);margin-bottom:0.4em;">How is the lesson sequenced?</div>
      <div style="font-size:10.5px;color:var(--muted);line-height:1.4;">A research-based set of elements — objective, input, modeling, practice, closure — for designing effective instruction.</div>
    </div>
  </div>
  <div class="card" style="padding:0;overflow:hidden;">
    <div style="background:var(--sage);padding:1.1em 0;display:flex;align-items:center;justify-content:center;">
      <div class="icon-circle" style="width:52px;height:52px;background:rgba(255,255,255,0.15);border:2px solid rgba(255,255,255,0.6);"><Icon name="layers" :size="24" color="#fff" /></div>
    </div>
    <div style="padding:0.9em;">
      <div class="badge" style="color:var(--sage);">Cognition</div>
      <div style="font-family:Cambria,Georgia,serif;font-weight:700;font-size:15px;color:var(--navy);margin:0.2em 0;">Bloom's Taxonomy</div>
      <div style="font-style:italic;font-weight:700;font-size:11px;color:var(--sage);margin-bottom:0.4em;">What kind of thinking is required?</div>
      <div style="font-size:10.5px;color:var(--muted);line-height:1.4;">A hierarchy of cognitive processes, from remembering facts to creating original work.</div>
    </div>
  </div>
  <div class="card" style="padding:0;overflow:hidden;">
    <div style="background:var(--rust);padding:1.1em 0;display:flex;align-items:center;justify-content:center;">
      <div class="icon-circle" style="width:52px;height:52px;background:rgba(255,255,255,0.15);border:2px solid rgba(255,255,255,0.6);"><Icon name="gauge" :size="24" color="#fff" /></div>
    </div>
    <div style="padding:0.9em;">
      <div class="badge" style="color:var(--rust);">Rigor</div>
      <div style="font-family:Cambria,Georgia,serif;font-weight:700;font-size:15px;color:var(--navy);margin:0.2em 0;">Depth of Knowledge</div>
      <div style="font-style:italic;font-weight:700;font-size:11px;color:var(--rust);margin-bottom:0.4em;">How deeply must students engage?</div>
      <div style="font-size:10.5px;color:var(--muted);line-height:1.4;">Webb's four levels of cognitive complexity — context, not just verb choice, drives the demand.</div>
    </div>
  </div>
  <div class="card" style="padding:0;overflow:hidden;">
    <div style="background:var(--navy2);padding:1.1em 0;display:flex;align-items:center;justify-content:center;">
      <div class="icon-circle" style="width:52px;height:52px;background:rgba(255,255,255,0.15);border:2px solid rgba(255,255,255,0.6);"><Icon name="flagTriangleRight" :size="24" color="#fff" /></div>
    </div>
    <div style="padding:0.9em;">
      <div class="badge" style="color:var(--navy2);">Accountability</div>
      <div style="font-family:Cambria,Georgia,serif;font-weight:700;font-size:15px;color:var(--navy);margin:0.2em 0;">State Standards</div>
      <div style="font-style:italic;font-weight:700;font-size:11px;color:var(--navy2);margin-bottom:0.4em;">What are students entitled to learn?</div>
      <div style="font-size:10.5px;color:var(--muted);line-height:1.4;">The non-negotiable target every objective, task, and assessment must trace back to.</div>
    </div>
  </div>
</div>

<div class="footer-bar"><span>Planning to Teach — Early-Service Teacher Series</span><span>3</span></div>

<!--
Here's the roadmap for the rest of this session. We're going to look at four frameworks, and it helps to think of each
one as answering a different question about your lesson. Madeline Hunter's model answers 'how is this lesson
sequenced' — it's about structure. Bloom's Taxonomy answers 'what kind of thinking am I actually asking students to
do.' Webb's Depth of Knowledge answers 'how deeply must students engage with this' — which, importantly, is a
different question than Bloom's, even though people often confuse the two. And state standards answer the
accountability question: what are students entitled to learn today, regardless of which teacher or classroom they're
in. None of these four replace each other. A strong daily plan uses all four at once.
-->

---

<div class="kicker">Framework 1 • Structure</div>
<h1 class="slide-title">Madeline Hunter's Elements of Lesson Design</h1>
<p class="lede">Hunter's research identified recurring elements present in effective lessons, regardless of grade level or subject (Hunter, 1982). They describe decision points a teacher makes — not a rigid script.</p>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:0.6em;">
  <div v-for="item in [
    ['1','Anticipatory Set','A short opener that focuses attention and links to prior learning.'],
    ['2','Objective & Purpose','What students will do, with what, and how well — and why it matters to them.'],
    ['3','Input','The vocabulary, concepts, and skills students need, delivered clearly.'],
    ['4','Modeling','The teacher demonstrates the thinking or skill using visible \u201cself-talk.\u201d'],
    ['5','Checking for Understanding','A formative check before releasing students to practice.'],
    ['6','Guided Practice','Students try the skill with the teacher circulating and coaching.'],
    ['7','Closure','Students articulate what they learned; the teacher confirms mastery.'],
    ['8','Independent Practice','Students apply the skill on their own, across new contexts.'],
  ]" :key="item[0]" class="card panel" style="display:flex;gap:0.7em;align-items:center;">
    <div class="numbered-circle">{{ item[0] }}</div>
    <div>
      <div style="font-weight:700;color:var(--navy);font-size:13px;">{{ item[1] }}</div>
      <div style="font-size:11px;color:var(--muted);line-height:1.3;">{{ item[2] }}</div>
    </div>
  </div>
</div>

<div class="footer-bar"><span>Planning to Teach — Early-Service Teacher Series</span><span>4</span></div>

<!--
Madeline Hunter developed her model of lesson design after studying what effective teachers actually did, across
grade levels and subjects, in her 1982 book Mastery Teaching. She identified eight recurring elements. You open with
an anticipatory set that hooks attention and connects to prior learning. You state the objective and purpose — what
students will do, with what, and how well, and why it matters. You deliver input: the vocabulary and concepts they
need. You model the thinking, often narrating your own thought process out loud. You check for understanding before
releasing students to practice. Guided practice comes next, with you actively coaching. Then closure, where students
articulate what they learned. And finally independent practice, where they apply the skill on their own. None of
these steps require equal time every day — but a strong planner is at least making a deliberate decision about each one.
-->

---

<div class="kicker rust">Framework 1 • Structure</div>
<h1 class="slide-title">A Framework for Thinking, Not a Checklist</h1>

<div style="display:grid;grid-template-columns:1.4fr 1fr;gap:1em;">
  <div class="card">
    <div style="display:flex;align-items:center;gap:0.7em;margin-bottom:0.6em;">
      <div class="icon-circle" style="background:var(--rust);"><Icon name="triangleAlert" :size="20" color="#fff" /></div>
      <div style="font-family:Cambria,Georgia,serif;font-weight:700;font-size:17px;color:var(--navy);">A Common Misapplication</div>
    </div>
    <p style="font-size:13px;line-height:1.55;">Hunter never proposed a mandatory "seven-step lesson plan." She offered elements for teachers to consider when making planning decisions — a platform for professional conversation about effective teaching, not a compliance checklist (Johnson, 2020).</p>
    <p style="font-size:13px;line-height:1.55;">When schools required every lesson to hit every element, in the same order, every day, the model became mechanical — and drew fair criticism for stifling teacher judgment and student-responsive teaching.</p>
    <div style="border-top:1px solid var(--line);margin:0.6em 0;"></div>
    <p style="font-size:13px;font-weight:700;font-style:italic;color:var(--navy);line-height:1.55;">Use the elements as a planning lens: which ones does today's content genuinely need, and in what order?</p>
  </div>

  <div style="display:flex;flex-direction:column;gap:0.8em;">
    <div class="card" style="background:#EDF3EC;border:none;">
      <div style="display:flex;align-items:center;gap:0.5em;margin-bottom:0.4em;">
        <div class="icon-circle" style="width:34px;height:34px;background:var(--sage);"><Icon name="circleCheck" :size="16" color="#fff" /></div>
        <div style="font-weight:700;color:var(--sage);font-size:14px;">Do</div>
      </div>
      <ul class="bullet-list">
        <li>Ask which elements this content needs.</li>
        <li>Compress or combine elements briefly.</li>
        <li>Use it to reflect on why a lesson stalled.</li>
      </ul>
    </div>
    <div class="card" style="background:#F4E9E5;border:none;">
      <div style="display:flex;align-items:center;gap:0.5em;margin-bottom:0.4em;">
        <div class="icon-circle" style="width:34px;height:34px;background:var(--rust);"><Icon name="triangleAlert" :size="16" color="#fff" /></div>
        <div style="font-weight:700;color:var(--rust);font-size:14px;">Don't</div>
      </div>
      <ul class="bullet-list">
        <li>Force all 8 steps into every lesson.</li>
        <li>Treat it as an evaluation checklist.</li>
        <li>Let sequence override student need.</li>
      </ul>
    </div>
  </div>
</div>

<div class="footer-bar"><span>Planning to Teach — Early-Service Teacher Series</span><span>5</span></div>

<!--
One important caution before we move on. Madeline Hunter herself objected to how her work was used. She never
proposed a mandatory seven-step lesson plan that every teacher had to follow in lockstep, in the same order, every
single day. Her intent, as Johnson documents in a 2020 piece, was to give teachers a shared vocabulary for talking
about effective teaching decisions. When districts turned it into a rigid checklist for teacher evaluation, it
became mechanical, and that's exactly what drew legitimate criticism. So as you plan, treat these elements as a
lens, not a script. Ask which ones today's content actually needs. Some days modeling takes eight minutes; other
days it takes ninety seconds because students already have the skill. The judgment is the point.
-->

---

<div class="kicker">Framework 2 • Cognition</div>
<h1 class="slide-title">Bloom's Taxonomy: Original and Revised</h1>
<p class="lede">Bloom's (1956) original taxonomy classified educational objectives into six cognitive levels. Anderson and Krathwohl's (2001) revision reframed the levels as verbs and added a knowledge dimension.</p>

<div style="display:grid;grid-template-columns:1.6fr 1fr;gap:1em;">
  <div>
    <div v-for="lvl in [
      ['Remember','Recognize, recall facts and basic concepts','var(--sage2)',34],
      ['Understand','Interpret, summarize, explain in your own words','var(--sage)',47],
      ['Apply','Execute, implement in a new situation','var(--olive)',60],
      ['Analyze','Differentiate, organize, attribute — break into parts','var(--gold)',73],
      ['Evaluate','Judge, critique, defend a position with evidence','var(--rust2)',86],
      ['Create','Design, construct, produce an original product','var(--rust)',99],
    ].slice().reverse()" :key="lvl[0]" :style="{background: lvl[2], width: lvl[3]+'%', borderRadius:'6px', padding:'0.35em 0.7em', marginBottom:'0.35em', color:'#fff'}">
      <div style="font-weight:700;font-size:13px;">{{ lvl[0] }}</div>
      <div style="font-size:10px;">{{ lvl[1] }}</div>
    </div>
    <div style="font-size:10.5px;font-style:italic;color:var(--muted);margin-top:0.3em;">Higher-order thinking ↑ &nbsp;&nbsp;&nbsp; Lower-order thinking ↓</div>
  </div>

  <div class="card navy">
    <div class="icon-circle" style="background:var(--gold);margin-bottom:0.6em;"><Icon name="brain" :size="20" color="#1B2A4A" /></div>
    <div style="font-family:Cambria,Georgia,serif;font-weight:700;font-size:15px;margin-bottom:0.5em;">What the 2001 Revision Changed</div>
    <ul class="bullet-list" style="color:var(--cream);">
      <li>Nouns became verbs (e.g., "Knowledge" → "Remember") — easier to write objectives with.</li>
      <li>Synthesis and Evaluation swapped order; Create became the top level.</li>
      <li>Added a knowledge dimension: factual, conceptual, procedural, metacognitive.</li>
    </ul>
  </div>
</div>

<div class="footer-bar"><span>Planning to Teach — Early-Service Teacher Series</span><span>6</span></div>

<!--
Bloom's Taxonomy is probably the most familiar framework here, but it's worth being precise about which version
you're using. Bloom's original 1956 taxonomy classified objectives into six levels, from Knowledge up through
Evaluation. In 2001, Anderson and Krathwohl led a revision that did three things: it turned the noun categories into
verbs, so 'Knowledge' became 'Remember' and 'Comprehension' became 'Understand,' which makes them much easier to
write objectives with; it swapped the order of the top two levels, so Create sits at the very top instead of
Evaluation; and it added a second dimension entirely — factual, conceptual, procedural, and metacognitive knowledge —
so you're classifying both the type of thinking and the type of knowledge involved. When you write a daily
objective, the verb you choose should genuinely reflect the level of thinking you want, not just a habit.
-->

---

<div class="kicker">Framework 2 • Cognition</div>
<h1 class="slide-title">Turning Bloom's Levels into Daily Objectives</h1>
<p class="lede">The verb you choose for a daily objective is a promise about the thinking students will actually do. Vague verbs ("understand," "know," "learn") hide the intended level; precise verbs make it visible and assessable.</p>

<div style="display:grid;grid-template-columns:repeat(3,1fr);gap:0.7em;">
  <div v-for="ex in [
    ['Remember','List the rhetorical appeals used in a persuasive speech.','var(--sage2)'],
    ['Understand','Summarize an author\'s central argument in one sentence.','var(--sage)'],
    ['Apply','Use MLA in-text citations correctly in a body paragraph.','var(--olive)'],
    ['Analyze','Differentiate a writer\'s claim from their supporting evidence.','var(--gold)'],
    ['Evaluate','Critique the strength of a peer\'s counterargument.','var(--rust2)'],
    ['Create','Compose an original argument that anticipates opposition.','var(--rust)'],
  ]" :key="ex[0]" class="card" :style="{borderLeft: '5px solid ' + ex[2]}">
    <div :style="{fontWeight:700, fontSize:'14px', color: ex[2]}">{{ ex[0] }}</div>
    <div style="font-size:10px;font-style:italic;color:var(--muted);margin:0.2em 0;">TLW (The learner will…)</div>
    <div style="font-size:12px;line-height:1.4;">{{ ex[1] }}</div>
  </div>
</div>

<div class="footer-bar"><span>Planning to Teach — Early-Service Teacher Series</span><span>7</span></div>

<!--
Here's the practical translation. Every one of these six objectives uses Hunter's TLW format — the learner will do
what, with what, how well — but the verb pins down exactly which Bloom's level is in play. 'List the rhetorical
appeals' is Remember. 'Summarize an author's argument' is Understand. Notice how each verb also implies a different
kind of evidence you'd collect to check mastery: a list, a one-sentence summary, a correctly formatted citation, a
comparison, a critique, an original piece of writing. When your daily objective's verb doesn't match the task you
actually assign, that's usually where a lesson quietly slides down to a lower level of thinking than you intended.
Checking that alignment is a two-minute habit worth building now.
-->

---

<div class="kicker">Framework 3 • Rigor</div>
<h1 class="slide-title">Webb's Depth of Knowledge: Four Levels</h1>
<p class="lede">DOK classifies the cognitive complexity required to complete a task — not its difficulty or the number of steps (Webb, 1997, 2002). It describes the context students must reason within.</p>

<div style="display:grid;grid-template-columns:repeat(4,1fr);gap:0.7em;">
  <div v-for="d in [
    ['1','Recall & Reproduction','Recall a fact, term, or procedure; perform a routine task.','Identify the tone of a poem\'s opening line.','var(--sage)'],
    ['2','Skills & Concepts','Use information or conceptual knowledge; two or more steps.','Classify examples of figurative language and explain each choice.','var(--olive)'],
    ['3','Strategic Thinking','Reason, plan, justify, and support with evidence; non-routine.','Support an interpretation of theme with textual evidence.','var(--gold)'],
    ['4','Extended Thinking','Investigate over time; synthesize across sources and contexts.','Research and defend a position across multiple texts and drafts.','var(--rust)'],
  ]" :key="d[0]" class="card" style="padding:0;overflow:hidden;">
    <div :style="{background:d[4], padding:'0.6em 0.8em'}">
      <div style="color:#fff;font-weight:700;font-size:11px;">DOK {{ d[0] }}</div>
      <div style="color:#fff;font-family:Cambria,Georgia,serif;font-weight:700;font-size:13px;">{{ d[1] }}</div>
    </div>
    <div style="padding:0.7em 0.8em;">
      <div style="font-size:10.5px;line-height:1.4;">{{ d[2] }}</div>
      <div style="border-top:1px solid var(--line);margin:0.5em 0;"></div>
      <div :style="{fontSize:'8.5px', fontWeight:700, color:d[4], letterSpacing:'0.05em'}">EXAMPLE</div>
      <div style="font-size:10px;font-style:italic;color:var(--muted);margin-top:0.2em;line-height:1.4;">{{ d[3] }}</div>
    </div>
  </div>
</div>

<div class="footer-bar"><span>Planning to Teach — Early-Service Teacher Series</span><span>8</span></div>

<!--
Depth of Knowledge comes from Norman Webb's work in 1997 and 2002, originally developed to judge how well
assessments align with standards. The key distinction to hold onto: DOK is not about difficulty or how many steps a
task has — it's about the cognitive complexity of the context students must reason within. Level 1 is recall and
reproduction: identifying, naming, performing a routine procedure. Level 2 is skills and concepts: using
information, classifying, applying a concept with two or more steps. Level 3 is strategic thinking: reasoning,
justifying, supporting an interpretation with evidence — this is where most rigorous discussion-based ELA work
lives. Level 4 is extended thinking: investigation over time, synthesizing across multiple sources, often a
multi-day research or writing task. A long worksheet with twenty Level 1 questions is still Level 1 — length
doesn't raise the DOK level.
-->

---

<div class="kicker">Frameworks 2 + 3 • Cognitive Rigor</div>
<h1 class="slide-title">Bloom's and DOK Are Complementary, Not Identical</h1>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1em;margin-bottom:0.8em;">
  <div class="card panel">
    <div class="icon-circle" style="background:var(--sage);margin-bottom:0.5em;"><Icon name="layers" :size="20" color="#fff" /></div>
    <div style="font-family:Cambria,Georgia,serif;font-weight:700;font-size:16px;color:var(--navy);">Bloom's Taxonomy</div>
    <div style="font-style:italic;font-weight:700;font-size:12.5px;color:var(--sage);margin:0.3em 0;">Asks: what TYPE of thinking?</div>
    <div style="font-size:12px;line-height:1.5;">Categorizes the cognitive process a task requires — remembering, applying, analyzing — using verbs. Best for writing clear learning objectives.</div>
  </div>
  <div class="card panel">
    <div class="icon-circle" style="background:var(--rust);margin-bottom:0.5em;"><Icon name="gauge" :size="20" color="#fff" /></div>
    <div style="font-family:Cambria,Georgia,serif;font-weight:700;font-size:16px;color:var(--navy);">Depth of Knowledge</div>
    <div style="font-style:italic;font-weight:700;font-size:12.5px;color:var(--rust);margin:0.3em 0;">Asks: how DEEPLY, in what context?</div>
    <div style="font-size:12px;line-height:1.5;">Categorizes the complexity of the context — transfer, evidence, extended engagement — regardless of verb. Best for judging task and assessment rigor.</div>
  </div>
</div>

<div class="card navy">
  <div style="display:flex;align-items:center;gap:0.6em;margin-bottom:0.4em;">
    <div class="icon-circle" style="background:var(--gold);"><Icon name="scale" :size="20" color="#1B2A4A" /></div>
    <div style="font-weight:700;color:var(--gold);font-size:14px;">The Same Verb Can Sit at Different DOK Levels</div>
  </div>
  <p style="font-size:12.5px;line-height:1.55;color:var(--cream);">"Analyze" a text's structure to identify parts is often DOK 2. "Analyze" a text to build and defend an original interpretation is DOK 3. A verb signals the type of thinking (Bloom's); the task's context, transfer demand, and evidence requirement determine the depth (DOK). Cognitive rigor comes from combining both dimensions with intention (Hess et al., 2009).</p>
</div>

<div class="footer-bar"><span>Planning to Teach — Early-Service Teacher Series</span><span>9</span></div>

<!--
This is the slide that clears up the most confusion, so let's slow down here. Bloom's Taxonomy and Depth of
Knowledge get mixed up constantly because both use a ladder of increasing complexity, but they measure different
things. Bloom's asks what type of thinking a task requires — remembering, applying, analyzing — and it's organized
around verbs. DOK asks how deeply, in what context, students must engage — and it's organized around the demands of
the task itself: does it require transfer to a new situation, does it require evidence and justification, does it
extend over time. Here's the concrete payoff: the same verb, 'analyze,' can sit at DOK 2 if students are just
identifying the parts of a structure, or DOK 3 if they're using that analysis to build and defend an original
interpretation. Hess and colleagues' 2009 work on cognitive rigor combines both dimensions into one matrix, which is
genuinely useful when you're designing a formative assessment and want to know if it truly matches your objective's
rigor.
-->

---

<div class="kicker">Framework 4 • Accountability</div>
<h1 class="slide-title">State Standards: The Anchor for Every Daily Plan</h1>
<p class="lede">Content standards describe what, not how, to teach — they define what every student is entitled to learn, regardless of teacher, classroom, or textbook (California Department of Education, 2013).</p>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:1em;">
  <div class="card">
    <div style="display:flex;align-items:center;gap:0.6em;margin-bottom:0.5em;">
      <div class="icon-circle" style="background:var(--navy2);"><Icon name="flagTriangleRight" :size="20" color="#fff" /></div>
      <div style="font-family:Cambria,Georgia,serif;font-weight:700;font-size:15.5px;color:var(--navy);">Why Standards Come First</div>
    </div>
    <ul class="bullet-list">
      <li>Standards are the legal and instructional floor — not a ceiling on rigor.</li>
      <li>They keep Bloom's/DOK choices purposeful instead of arbitrary.</li>
      <li>They give every teacher in the district a shared reference point for coherence across sections and years.</li>
      <li>They are the thread that later connects daily plans into a coherent catalog.</li>
    </ul>
  </div>

  <div class="card navy">
    <div style="display:flex;align-items:center;gap:0.6em;margin-bottom:0.5em;">
      <div class="icon-circle" style="background:var(--gold);"><Icon name="arrowRight" :size="20" color="#1B2A4A" /></div>
      <div style="font-family:Cambria,Georgia,serif;font-weight:700;font-size:15px;">From Standard to Daily Objective</div>
    </div>
    <div v-for="c in [
      ['STANDARD','CCSS.ELA-Literacy.W.11-12.1 — Write arguments to support claims using valid reasoning and sufficient evidence.'],
      ['BLOOM\'S LEVEL','Create + Evaluate — students construct and defend an original argument.'],
      ['DOK TARGET','DOK 3 — reasoning and justification with textual evidence.'],
      ['DAILY OBJECTIVE','TLW draft a claim and two lines of reasoning for a rhetorical analysis essay, citing textual evidence.'],
    ]" :key="c[0]" style="margin-bottom:0.55em;">
      <div style="font-size:9px;font-weight:700;color:var(--gold);letter-spacing:0.06em;">{{ c[0] }}</div>
      <div style="font-size:11px;color:#fff;line-height:1.35;">{{ c[1] }}</div>
    </div>
  </div>
</div>

<div class="footer-bar"><span>Planning to Teach — Early-Service Teacher Series</span><span>10</span></div>

<!--
The fourth framework isn't optional or supplementary — it's the anchor everything else attaches to. State content
standards, like California's adoption of the Common Core State Standards for English Language Arts, describe what
students are expected to know and be able to do at each grade level. Standards describe the what, not the how —
that's intentional. It means Hunter's structure, Bloom's cognitive level, and Webb's DOK target are all decisions
you make about how to teach toward a standard, not decisions that replace it. Look at the worked example: we start
with an actual writing standard, decide it calls for Create and Evaluate-level thinking on Bloom's scale, target DOK
3 because students need to reason and justify with evidence, and only then write the specific daily objective. If
you can't trace your daily objective back to a standard in one sentence, that's worth revisiting before you teach
the lesson.
-->

---

<div class="kicker">Synthesis</div>
<h1 class="slide-title">The Integrated Daily Plan</h1>
<p class="lede">One template, four frameworks working together — this is what you actually fill out each day.</p>

<div style="display:grid;grid-template-columns:1fr 1fr;gap:0.55em;">
  <div v-for="it in [
    ['flagTriangleRight','var(--navy2)','Standard','The exact code and language of the state standard this lesson serves.'],
    ['target','var(--sage)','Objective (TLW)','A Bloom\'s-calibrated verb + content + criterion for success.'],
    ['gauge','var(--rust)','DOK Target','The intended depth — named explicitly, so tasks are checked against it.'],
    ['lightbulb','var(--gold)','Anticipatory Set','Hunter Element 1 — how attention connects to prior learning.'],
    ['bookOpen','var(--navy2)','Input & Modeling','Hunter Elements 3–4 — what\'s taught and how it\'s demonstrated.'],
    ['fileSearch','var(--sage)','Checking for Understanding','Hunter Element 5 — the formative gate before practice.'],
    ['users','var(--rust)','Guided → Independent Practice','Hunter Elements 6 & 8 — scaffolded release of responsibility.'],
    ['circleCheck','var(--gold)','Closure','Hunter Element 7 — how students prove today\'s learning, tied to the objective.'],
  ]" :key="it[2]" class="card" style="display:flex;gap:0.6em;align-items:center;">
    <div class="icon-circle" :style="{background: it[1]}"><Icon :name="it[0]" :size="18" color="#fff" /></div>
    <div>
      <div style="font-weight:700;color:var(--navy);font-size:12.5px;">{{ it[2] }}</div>
      <div style="font-size:10px;color:var(--muted);line-height:1.3;">{{ it[3] }}</div>
    </div>
  </div>
</div>

<div class="footer-bar"><span>Planning to Teach — Early-Service Teacher Series</span><span>11</span></div>

<!--
Put all four frameworks together and here's what your actual daily plan template looks like. It starts with the
standard, in exact language, not a paraphrase. Then the objective, written in TLW format with a Bloom's-calibrated
verb. Then the DOK target, named explicitly — writing 'DOK 3' at the top of your plan is a small habit that keeps
you honest about whether your actual task matches it. From there, the rest of the plan follows Hunter's elements:
anticipatory set, input and modeling, checking for understanding, guided and independent practice, and closure that
ties directly back to the objective you started with. This single template is the unit of everything we're about to
discuss next — because once you're filling this out daily, you're producing something far more valuable than a
lesson plan for tomorrow.
-->

---

<div class="kicker">From Daily Practice to Institutional Memory</div>
<h1 class="slide-title">Every Daily Plan Is Raw Material — Don't Discard It</h1>
<p style="font-size:14px;line-height:1.5;margin-bottom:1em;">A daily plan written and thrown away teaches you once. A daily plan filed, tagged, and kept becomes a reusable, improvable asset — the beginning of a personal curriculum catalog.</p>

<div style="display:grid;grid-template-columns:repeat(4,1fr);gap:0.7em;">
  <div v-for="r in [
    ['folderOpen','var(--navy2)','Nothing Is Rewritten From Scratch','Next year\'s version of today\'s lesson starts as a revision, not a blank page — compounding your planning efficiency year over year.'],
    ['fileSearch','var(--sage)','Gaps and Redundancies Surface','A catalog of dated, standard-tagged plans makes it visible where a standard was never taught — or was taught three times.'],
    ['users','var(--rust)','Collaboration Becomes Possible','Colleagues and future you can see what was actually taught, not just what was intended — the same shift Jacobs (1997) documented.'],
    ['trendingUp','var(--gold)','A Foundation for Growth','Patterns across dozens of saved plans reveal your own instructional habits — where rigor consistently lands and where it doesn\'t.'],
  ]" :key="r[2]" class="card panel" style="text-align:center;">
    <div class="icon-circle" :style="{background: r[1], margin:'0 auto 0.6em'}"><Icon :name="r[0]" :size="20" color="#fff" /></div>
    <div style="font-family:Cambria,Georgia,serif;font-weight:700;font-size:13px;color:var(--navy);margin-bottom:0.4em;">{{ r[2] }}</div>
    <div style="font-size:10.5px;color:var(--muted);line-height:1.4;">{{ r[3] }}</div>
  </div>
</div>

<div class="footer-bar"><span>Planning to Teach — Early-Service Teacher Series</span><span>12</span></div>

<!--
Here's the pivot for the rest of this session. Everything so far has been about making one day's plan strong. But a
single plan, written and then discarded after the bell rings, only teaches you once. The same plan, filed and
tagged, becomes something much more valuable. Four things happen when you keep every plan. First, nothing gets
rewritten from scratch — next year's version of today's lesson starts as a revision. Second, gaps and redundancies
become visible; you can literally see, across a semester, if a standard never got taught or got taught three times
by accident. Third, collaboration becomes possible, because colleagues can see what was actually taught, not just
what was intended — this is the same shift Heidi Hayes Jacobs documented in 1997 when she introduced curriculum
mapping to K-12 schools. And fourth, patterns across dozens of saved plans start to reveal your own instructional
habits. This is why we ask you to build a catalog, not just a folder of one-off lessons.
-->

---

<div class="kicker">Practical Routine</div>
<h1 class="slide-title">Building the Catalog: A Practical Weekly Routine</h1>
<p class="lede">A simple, repeatable habit — not a large project — is what actually produces a usable catalog by year's end.</p>

<div style="display:flex;flex-direction:column;gap:0.6em;">
  <div v-for="st in [
    ['1','File it the same day','Save each daily plan immediately, in one consistent folder structure by course, unit, and date — never scattered across desks or devices.'],
    ['2','Tag it','Label each plan with its standard code, Bloom\'s level, and DOK target so it\'s searchable later, not just archived.'],
    ['3','Note what actually happened','Add one line after teaching: what worked, what you\'d change, how long it really took — the taught curriculum, not just the planned one (Jacobs, 1997).'],
    ['4','Review monthly','Scan the month\'s plans against your standards list. Look for a skipped standard or an accidental repeat before it becomes a pattern.'],
  ]" :key="st[0]" style="display:flex;gap:0.8em;align-items:center;">
    <div class="numbered-circle">{{ st[0] }}</div>
    <div class="card" style="flex:1;display:grid;grid-template-columns:220px 1fr;gap:1em;align-items:center;">
      <div style="font-weight:700;color:var(--navy);font-size:13px;">{{ st[1] }}</div>
      <div style="font-size:11.5px;color:var(--muted);line-height:1.4;">{{ st[2] }}</div>
    </div>
  </div>
</div>

<div class="footer-bar"><span>Planning to Teach — Early-Service Teacher Series</span><span>13</span></div>

<!--
Building a catalog sounds like a big project, but it's really four small habits, repeated. First, file each plan the
same day you teach it, in a consistent folder structure by course, unit, and date — consistency matters more than
the specific system you choose. Second, tag it: standard code, Bloom's level, DOK target, so a future search actually
surfaces it. Third — and this is the step people skip — add one line after teaching about what actually happened:
what worked, what you'd change, how long it really took. Jacobs' 1997 work on curriculum mapping calls this
capturing the 'taught curriculum' rather than just the planned one, and it's the single most valuable line in the
whole file a year later. Fourth, review monthly: scan the month against your standards list and catch a skipped
standard before it becomes a pattern instead of a mistake.
-->

---

<div class="kicker">The Long View</div>
<h1 class="slide-title">From Catalog to a Year-to-Year Program</h1>
<p class="lede">Curriculum mapping formalizes what a well-kept catalog already contains — turning daily plans into a coherent, reviewable program across the year (Jacobs, 1997).</p>

<div style="display:grid;grid-template-columns:repeat(4,1fr);gap:0.8em;margin-bottom:0.9em;align-items:stretch;">
  <div v-for="(st,i) in [
    ['clipboardList','var(--navy2)','Daily Plan','One lesson, one standard, tagged and filed.'],
    ['folderOpen','var(--sage)','Weekly / Unit Catalog','Plans grouped by unit reveal sequence and pacing.'],
    ['calendarRange','var(--gold)','Semester Map','Standards coverage checked against the full term.'],
    ['compass','var(--rust)','Year-to-Year Program','A living map revised each year from real classroom data.'],
  ]" :key="st[2]" class="card" style="text-align:center;position:relative;">
    <div class="icon-circle" :style="{background: st[1], margin:'0 auto 0.6em'}"><Icon :name="st[0]" :size="20" color="#fff" /></div>
    <div style="font-family:Cambria,Georgia,serif;font-weight:700;font-size:13px;color:var(--navy);margin-bottom:0.4em;">{{ st[2] }}</div>
    <div style="font-size:10.5px;color:var(--muted);line-height:1.4;">{{ st[3] }}</div>
  </div>
</div>

<div class="card navy">
  <p style="font-size:12.5px;font-style:italic;color:var(--cream);line-height:1.55;margin:0;">A curriculum map is calendar-based and reviewed continuously — not written once and shelved. It shows not just what should be taught, but, drawn from your catalog, what was actually taught, when, and how well it worked (Jacobs, 1997).</p>
</div>

<div class="footer-bar"><span>Planning to Teach — Early-Service Teacher Series</span><span>14</span></div>

<!--
This is the payoff. A daily plan catalog, kept consistently, naturally scales upward. Grouped by unit, it reveals
your actual sequence and pacing — how many days a unit really took versus what you planned. Rolled up by semester,
you can check standards coverage against the full term, not just guess at it in June. And across years, it becomes
what Heidi Hayes Jacobs called curriculum mapping in her 1997 book Mapping the Big Picture: a calendar-based,
continuously reviewed map of what's actually taught, not a document written once at the start of the year and never
touched again. The critical distinction Jacobs makes is between the intended curriculum — what a pacing guide says —
and the taught curriculum — what your catalog of daily plans actually shows happened. Your year-to-year program
should be built from the second one.
-->

---
class: dark-bg
---

<div class="dark-bg" style="position:absolute;inset:0;overflow:hidden;">
  <div style="position:absolute;bottom:-140px;right:-100px;width:340px;height:340px;border-radius:999px;background:var(--navy2);"></div>
</div>

<div style="position:relative;">
  <div class="kicker" style="color:var(--gold);">Your First 90 Days</div>
  <h1 class="slide-title" style="color:#fff;">A Starter Checklist for New Teachers</h1>
  <p style="font-size:13.5px;color:var(--cream);margin-bottom:1em;">Small, consistent habits — not a perfect system on day one — build the catalog that carries you into year two.</p>

  <div style="display:grid;grid-template-columns:1fr 1fr;gap:0.5em 1.5em;">
    <div v-for="c in [
      'Use the Hunter elements as a planning lens for every daily plan — not a rigid checklist.',
      'Write every objective in TLW format with a deliberate, Bloom\'s-calibrated verb.',
      'Name a DOK target explicitly, and check your task actually matches it.',
      'Anchor every objective to one exact standard code — no paraphrasing.',
      'File and tag every daily plan the same day you teach it.',
      'Add one reflection line per lesson: what actually happened.',
      'Review your catalog monthly against your standards list.',
      'Revisit and revise last year\'s plans instead of starting blank — that\'s the beginning of your program.',
    ]" :key="c" style="display:flex;gap:0.6em;align-items:center;">
      <div class="icon-circle" style="width:34px;height:34px;background:var(--gold);flex-shrink:0;"><Icon name="circleCheck" :size="16" color="#1B2A4A" /></div>
      <div style="font-size:12px;color:#fff;line-height:1.35;">{{ c }}</div>
    </div>
  </div>
</div>

<div class="footer-bar"><span>Planning to Teach — Early-Service Teacher Series</span><span>15</span></div>

<!--
As you get started, here's the short version to keep on your desk. Use Hunter's elements as a lens for your planning
decisions, not a rigid checklist. Write every objective in TLW format with a verb you actually chose on purpose from
Bloom's taxonomy. Name your DOK target explicitly and check that your task matches it. Anchor every single
objective to one exact standard code — resist the urge to paraphrase it from memory. File and tag every plan the
same day you teach it, and add one honest reflection line about what actually happened. Review your catalog monthly
against your standards list. And starting in year two, revisit and revise last year's plans instead of starting
from a blank page — that revision habit is the moment your daily plans officially become a program. None of this
needs to be perfect on day one. It needs to be consistent.
-->

---

<div class="kicker">References</div>
<h1 class="slide-title">References</h1>

<div style="font-size:12.5px;line-height:1.6;">
  <p style="padding-left:1.6em;text-indent:-1.6em;margin-bottom:0.7em;">Anderson, L. W., &amp; Krathwohl, D. R. (Eds.). (2001). <em>A taxonomy for learning, teaching, and assessing: A revision of Bloom's taxonomy of educational objectives</em> (Complete ed.). Longman.</p>
  <p style="padding-left:1.6em;text-indent:-1.6em;margin-bottom:0.7em;">Bloom, B. S. (Ed.). (1956). <em>Taxonomy of educational objectives: The classification of educational goals. Handbook I: Cognitive domain.</em> David McKay.</p>
  <p style="padding-left:1.6em;text-indent:-1.6em;margin-bottom:0.7em;">California Department of Education. (2013). <em>California common core state standards: English language arts and literacy in history/social studies, science, and technical subjects.</em> California Department of Education.</p>
  <p style="padding-left:1.6em;text-indent:-1.6em;margin-bottom:0.7em;">Hess, K. K., Jones, B. S., Carlock, D., &amp; Walkup, J. R. (2009). <em>Cognitive rigor: Blending the strengths of Bloom's taxonomy and Webb's depth of knowledge to enhance classroom-level processes.</em> ERIC Clearinghouse.</p>
  <p style="padding-left:1.6em;text-indent:-1.6em;margin-bottom:0.7em;">Hunter, M. (1982). <em>Mastery teaching.</em> TIP Publications.</p>
  <p style="padding-left:1.6em;text-indent:-1.6em;margin-bottom:0.7em;">Jacobs, H. H. (1997). <em>Mapping the big picture: Integrating curriculum &amp; assessment, K–12.</em> Association for Supervision and Curriculum Development.</p>
  <p style="padding-left:1.6em;text-indent:-1.6em;margin-bottom:0.7em;">John, P. D. (2006). Lesson planning and the student teacher: Re-thinking the dominant model. <em>Journal of Curriculum Studies, 38</em>(4), 483–498. https://doi.org/10.1080/00220270500363620</p>
  <p style="padding-left:1.6em;text-indent:-1.6em;margin-bottom:0.7em;">Johnson, A. P. (2020). <em>The Hunter lesson plan format and other teaching recipes.</em> Cornerstone: A Collection of Scholarly and Creative Works, Minnesota State University, Mankato.</p>
  <p style="padding-left:1.6em;text-indent:-1.6em;margin-bottom:0.7em;">Webb, N. L. (1997). <em>Criteria for alignment of expectations and assessments in mathematics and science education</em> (Research Monograph No. 6). Council of Chief State School Officers; Wisconsin Center for Education Research.</p>
  <p style="padding-left:1.6em;text-indent:-1.6em;margin-bottom:0.7em;">Webb, N. L. (2002). <em>Depth-of-knowledge levels for four content areas</em> [Unpublished manuscript]. Wisconsin Center for Education Research.</p>
</div>

<div class="footer-bar"><span>Planning to Teach — Early-Service Teacher Series</span><span>16</span></div>

<!--
These are the sources behind everything we covered today — Hunter's original work on mastery teaching, Bloom's
original taxonomy alongside Anderson and Krathwohl's 2001 revision, Webb's foundational papers on Depth of
Knowledge, Hess and colleagues' work combining Bloom's and DOK into a single cognitive rigor framework, Jacobs'
foundational text on curriculum mapping, John's research on novice versus expert planning, and the California
Common Core State Standards for English Language Arts. I'd encourage you to read Hunter and Jacobs in particular in
your first year — they're short, practical, and written for classroom teachers, not just researchers. Thank you —
I'm happy to work through your own daily plan template together whenever you're ready.
-->
