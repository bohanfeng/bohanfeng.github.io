---
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
.page__content hr {
  margin: 0.95em 0;
}
.page__content hr + h2 {
  margin-top: 0.75em;
}
.page__content h2 {
  margin-bottom: 0.75em;
  padding-bottom: 0.45em;
}
.hero-note {
  margin: 1.2em 0 2em;
  padding: 1em 1.2em;
  border-left: 4px solid #2f5d8a;
  background: rgba(47, 93, 138, 0.06);
  border-radius: 6px;
}
.hero-note p:last-child {
  margin-bottom: 0;
}
.edu-cards {
  display: flex;
  gap: 1em;
  flex-wrap: wrap;
  margin: 1.2em 0 2em;
}
.edu-card {
  flex: 1;
  min-width: 260px;
  border: 1px solid #e0e0e0;
  border-radius: 8px;
  padding: 1.2em 1.5em;
}
.edu-card__header {
  position: relative;
  padding-right: 96px;
  margin-bottom: 0.35em;
}
.edu-card__text {
  min-width: 0;
}
.edu-card__logo {
  width: 73px;
  height: 73px;
  object-fit: contain;
  position: absolute;
  top: 0;
  right: 0;
}
.edu-card__degree {
  font-weight: 700;
  font-size: 0.96em;
  margin-bottom: 0.25em;
}
.edu-card__school {
  font-size: 0.88em;
  line-height: 1.35;
}
.edu-card__period {
  color: #777;
  font-size: 0.82em;
  margin-bottom: 0.45em;
}
.edu-card__detail {
  font-size: 0.88em;
  line-height: 1.7;
  color: #555;
}
.theme-grid {
  display: flex;
  flex-direction: column;
  gap: 1em;
  margin: 1.35em 0 2em;
}
.theme-card {
  display: flex;
  align-items: center;
  gap: 1.1em;
  border: 1px solid #e0e0e0;
  border-radius: 12px;
  padding: 1.05em 1.2em;
  background: #fff;
}
.theme-card__visual {
  position: relative;
  width: 126px;
  height: 96px;
  flex: 0 0 126px;
  border-radius: 16px;
  overflow: hidden;
  border: 1px solid #dce6ef;
  background: #fff;
}
.theme-card__image {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}
.theme-card__visual::before {
  content: "";
  position: absolute;
  inset: 0;
  background:
    radial-gradient(circle at 18% 22%, rgba(47, 93, 138, 0.16), transparent 22%),
    radial-gradient(circle at 82% 78%, rgba(224, 112, 90, 0.16), transparent 20%);
}
.theme-card__glyph {
  position: absolute;
  inset: 0;
}
.theme-card__content {
  flex: 1;
  min-width: 0;
}
.theme-card__index {
  display: inline-block;
  margin-bottom: 0.45em;
  padding: 0.22em 0.58em;
  border-radius: 999px;
  background: rgba(47, 93, 138, 0.12);
  color: #2f5d8a;
  font-size: 0.74em;
  font-weight: 700;
  letter-spacing: 0.04em;
  text-transform: uppercase;
}
.theme-card__title {
  font-weight: 700;
  line-height: 1.42;
  margin-bottom: 0.4em;
}
.theme-card__body {
  font-size: 0.9em;
  color: #555;
  line-height: 1.7;
  margin: 0;
}
.theme-card__visual::before,
.theme-card__visual::after,
.theme-card__glyph,
.theme-card__glyph::before,
.theme-card__glyph::after {
  display: none !important;
  content: none !important;
}
.theme-card__visual--one .theme-card__glyph::before {
  content: "";
  position: absolute;
  inset: 18px 20px;
  border: 2px dashed rgba(47, 93, 138, 0.32);
  border-radius: 26px;
}
.theme-card__visual--one .theme-card__glyph::after {
  content: "";
  position: absolute;
  width: 16px;
  height: 16px;
  top: 50%;
  left: 50%;
  margin: -8px 0 0 -8px;
  border-radius: 50%;
  background: linear-gradient(135deg, #2f5d8a, #2f7f93);
  box-shadow: 0 0 0 6px rgba(47, 93, 138, 0.10);
  animation: theme-orbit 4.6s linear infinite;
}
.theme-card__visual--one::after {
  content: "";
  position: absolute;
  width: 12px;
  height: 12px;
  border-radius: 50%;
  background: #e0705a;
  top: 22px;
  left: 24px;
  box-shadow: 64px 42px 0 0 rgba(47, 127, 147, 0.85);
  animation: theme-pulse 2.6s ease-in-out infinite;
}
.theme-card__visual--two .theme-card__glyph {
  position: absolute;
  left: 24px;
  right: 24px;
  top: 50%;
  height: 10px;
  margin-top: -5px;
  border-radius: 999px;
  background: linear-gradient(90deg, rgba(47, 93, 138, 0.24), rgba(47, 127, 147, 0.45), rgba(224, 112, 90, 0.24));
  animation: theme-breathe 2.8s ease-in-out infinite;
}
.theme-card__visual--two .theme-card__glyph::before,
.theme-card__visual--two .theme-card__glyph::after {
  content: "";
  position: absolute;
  top: 50%;
  width: 22px;
  height: 22px;
  margin-top: -11px;
  border-radius: 50%;
  box-shadow: 0 0 0 8px rgba(47, 93, 138, 0.10);
}
.theme-card__visual--two .theme-card__glyph::before {
  left: -8px;
  background: #2f5d8a;
  animation: theme-pulse 2.4s ease-in-out infinite;
}
.theme-card__visual--two .theme-card__glyph::after {
  right: -8px;
  background: #e0705a;
  animation: theme-pulse 2.4s ease-in-out infinite 0.5s;
}
.theme-card__visual--three .theme-card__glyph {
  position: absolute;
  left: 24px;
  right: 24px;
  bottom: 20px;
  height: 12px;
  border-radius: 999px;
  background: rgba(47, 93, 138, 0.14);
}
.theme-card__visual--three .theme-card__glyph::before {
  content: "";
  position: absolute;
  left: 50%;
  bottom: 10px;
  width: 26px;
  height: 42px;
  margin-left: -13px;
  border-radius: 14px 14px 8px 8px;
  background: linear-gradient(180deg, #2f7f93, #2f5d8a);
  box-shadow: 0 8px 18px rgba(47, 93, 138, 0.18);
  animation: theme-sweep 2.8s ease-in-out infinite;
}
.theme-card__visual--three .theme-card__glyph::after {
  content: "";
  position: absolute;
  left: 16px;
  right: 16px;
  bottom: 26px;
  height: 22px;
  border-top: 3px solid rgba(224, 112, 90, 0.8);
  border-radius: 50%;
  animation: theme-wave 2.6s ease-in-out infinite;
}
@keyframes theme-orbit {
  from {
    transform: rotate(0deg) translateX(29px) rotate(0deg);
  }
  to {
    transform: rotate(360deg) translateX(29px) rotate(-360deg);
  }
}
@keyframes theme-pulse {
  0%, 100% {
    transform: scale(1);
    opacity: 0.88;
  }
  50% {
    transform: scale(1.18);
    opacity: 1;
  }
}
@keyframes theme-breathe {
  0%, 100% {
    transform: scaleX(0.94);
    opacity: 0.72;
  }
  50% {
    transform: scaleX(1.04);
    opacity: 1;
  }
}
@keyframes theme-sweep {
  0%, 100% {
    transform: translateX(-12px) rotate(-8deg);
  }
  50% {
    transform: translateX(12px) rotate(8deg);
  }
}
@keyframes theme-wave {
  0%, 100% {
    transform: scaleX(0.88);
    opacity: 0.4;
  }
  50% {
    transform: scaleX(1.08);
    opacity: 0.95;
  }
}
@media (prefers-reduced-motion: reduce) {
  .theme-card__visual *,
  .theme-card__visual::after {
    animation: none !important;
  }
}
.career-card {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 1.25em;
  margin: 1.2em 0 2em;
  padding: 1.1em 1.3em;
  border: 1px solid #d9e2ec;
  border-radius: 8px;
  background: #fafcfe;
}
.career-card__text {
  flex: 1;
}
.career-card__text p:last-child {
  margin-bottom: 0;
}
.career-card__logo {
  width: 198px;
  height: auto;
  object-fit: contain;
  flex: 0 0 198px;
}
@media (max-width: 900px) {
  .edu-card__header {
    padding-right: 88px;
  }
  .theme-card {
    flex-direction: column;
    align-items: flex-start;
  }
  .theme-card__visual {
    width: 100%;
    max-width: 180px;
  }
  .career-card {
    flex-direction: column;
    align-items: flex-start;
  }
  .career-card__logo {
    width: 150px;
    flex-basis: 150px;
    margin: 0.4em auto 0;
  }
}
</style>

<div class="lang-zh" markdown="1">

# 冯波瀚 | Bohan Feng (Dylan Bo)
**讲师，机器人工艺与智能制造研究者**

您好。我目前任职于[上海交通大学溥渊未来技术学院（GIFT）](https://gift.sjtu.edu.cn/)，并隶属于[Smart Manufacturing with AI and Reliability Technology (SMART) Center](https://gift.sjtu.edu.cn/research/60)。我当前与[倪军](https://gift.sjtu.edu.cn/faculty/40815)教授和[金隼](https://me.sjtu.edu.cn/teacher_directory1/jinsun)教授合作，研究聚焦于**复杂制造中的机器人工艺质量形成机理与主动调控**。
</div>

<div class="lang-en" markdown="1">

# Bohan Feng (Dylan Bo) | 冯波瀚
**Lecturer, Robotic Manufacturing Process Researcher**

I am a Lecturer at the [Global Institute of Future Technology (GIFT), Shanghai Jiao Tong University](https://gift.sjtu.edu.cn/en), affiliated with the [Smart Manufacturing with AI and Reliability Technology (SMART) Center](https://gift.sjtu.edu.cn/en/research/10060). I am currently working with [Jun Ni](https://gift.sjtu.edu.cn/en/faculty/40816) and [Sun Jin](https://me.sjtu.edu.cn/en/FullTimeTeacher/jinsun.html) on **the mechanisms, dynamical structure, and active regulation of process quality formation in robotic manufacturing**, treating quality not as a downstream error metric but as an emergent property of coupled robot-tool-workpiece-process systems. My name is written in Chinese as **冯波瀚**, which is the name most commonly used in Chinese-language search.

</div>

<div class="hero-note">
  <div class="lang-zh" markdown="1">
  我的长期目标，是推动“机器人制造工艺学”从经验驱动走向复杂动力系统科学：将机器人—刀具—工件—工艺过程理解为一个**多体、多场、多尺度、强耦合的非线性系统**，揭示其在参数空间中的**全局拓扑结构、吸引子、奇异性与临界行为**，并据此建立面向质量形成的**可建模、可预测、可设计、可调控**理论体系。
  </div>
  <div class="lang-en" markdown="1">
  My long-term goal is to help build a science of **robotic manufacturing process quality** by treating robot-tool-workpiece-process interactions as a **multibody, multiphysics, multiscale, and strongly coupled nonlinear dynamical system**, uncovering its **global topological structure in parameter space, including attractors, singularities, and critical behaviors**, and using that understanding to establish a theory of quality formation that is **modelable, predictable, designable, and actively regulatable**.
  </div>
</div>

---

## <span class="lang-zh">教育背景</span><span class="lang-en">Education</span>

<div class="edu-cards">
  <div class="edu-card">
    <div class="edu-card__header">
      <div class="edu-card__text">
        <div class="edu-card__degree">
          <span class="lang-zh">控制科学与工程 博士</span>
          <span class="lang-en">Ph.D. in Control Science and Engineering</span>
        </div>
        <div class="edu-card__school">
          <span class="lang-zh">上海交通大学</span>
          <span class="lang-en">Shanghai Jiao Tong University</span>
        </div>
      </div>
      <img class="edu-card__logo" src="/images/education/sjtu.svg" alt="SJTU logo">
    </div>
    <div class="edu-card__period">2020 - 2025</div>
    <div class="edu-card__detail">
      <span class="lang-zh">GPA：3.7 / 4.0<br>导师：毕有益教授</span>
      <span class="lang-en">GPA: 3.7 / 4.0<br>Advisor: Prof. Youyi Bi</span>
    </div>
  </div>
  <div class="edu-card">
    <div class="edu-card__header">
      <div class="edu-card__text">
        <div class="edu-card__degree">
          <span class="lang-zh">计算机科学与技术 学士</span>
          <span class="lang-en">B.Eng. in Computer Science and Technology</span>
        </div>
        <div class="edu-card__school">
          <span class="lang-zh">大连理工大学</span>
          <span class="lang-en">Dalian University of Technology</span>
        </div>
      </div>
      <img class="edu-card__logo" src="/images/education/dlut.svg" alt="DLUT logo">
    </div>
    <div class="edu-card__period">2016 - 2020</div>
    <div class="edu-card__detail">
      <span class="lang-zh">GPA：3.9 / 4.0<br>创新实验班</span>
      <span class="lang-en">GPA: 3.9 / 4.0<br>Innovation Experimental Class</span>
    </div>
  </div>
</div>

---

## <span class="lang-zh">核心研究问题</span><span class="lang-en">Core Research Question</span>

<div class="lang-zh" markdown="1">
在复杂制造中，如果将工艺质量视为机器人—刀具—工件—工艺过程耦合动力系统中的涌现现象，而不是事后修正的下游结果，如何以具备原理性的方式将质量要求转化为机器人运动、姿态与交互策略？
</div>

<div class="lang-en" markdown="1">
**In complex manufacturing, if process quality is understood as an emergent property of a coupled robot-tool-workpiece-process dynamical system rather than a downstream outcome to be corrected post hoc, how can process-quality requirements be translated into robotic motion, posture, and interaction strategies in a principled way?**
</div>

---

## <span class="lang-zh">研究主线</span><span class="lang-en">Research Agenda</span>

<div class="theme-grid">
  <div class="theme-card">
    <div class="theme-card__visual theme-card__visual--one" aria-hidden="true">
      <img class="theme-card__image" src="/images/research-agenda/theme-1.webp" alt="Theme 1 illustration">
    </div>
    <div class="theme-card__content">
      <div class="theme-card__index">Theme 1</div>
      <div class="theme-card__title">
        <span class="lang-zh">工艺质量驱动的机器人行为生成</span>
        <span class="lang-en">Process-Quality-Driven Robot Behavior Generation</span>
      </div>
      <p class="theme-card__body">
        <span class="lang-zh">研究路径、轨迹、姿态、节拍与操作参数如何围绕工艺质量目标联合生成，使机器人行为直接面向质量相关的几何约束、动力学约束与过程状态演化，而不是先规划再事后修补；重点关注运动规划、学习型生成、多机器人协同与数字孪生驱动的行为设计。</span>
        <span class="lang-en">I study how paths, trajectories, postures, timing, and operation parameters can be generated jointly around process-quality objectives, so that robot behavior is synthesized directly against quality-relevant geometric constraints, dynamical constraints, and process-state evolution rather than planned first and corrected later. This includes motion planning, learning-based generation, multi-robot coordination, and digital-twin-enabled behavior design.</span>
      </p>
    </div>
  </div>
  <div class="theme-card">
    <div class="theme-card__visual theme-card__visual--two" aria-hidden="true">
      <img class="theme-card__image" src="/images/research-agenda/theme-2.webp" alt="Theme 2 illustration">
    </div>
    <div class="theme-card__content">
      <div class="theme-card__index">Theme 2</div>
      <div class="theme-card__title">
        <span class="lang-zh">人机协同下的工艺认知与质量共调控</span>
        <span class="lang-en">Human-in-the-Loop Process Cognition and Co-Regulation</span>
      </div>
      <p class="theme-card__body">
        <span class="lang-zh">研究人的知识、经验、示教与认知反馈如何进入机器人制造过程，形成面向工艺质量的协同调控回路，尤其关注当过程状态部分不可观、具有安全风险或接近失稳边界时，人如何从外部监督者转变为工艺认知与质量调控的一部分。</span>
        <span class="lang-en">I investigate how human knowledge, experience, teaching, and cognitive feedback can enter robotic manufacturing as part of a process-quality co-regulation loop, especially when process states are partially observed, safety-critical, or close to instability boundaries. The goal is to turn human participation from external supervision into a structured source of process cognition for shared-workspace collaboration, tool use, and complex task execution.</span>
      </p>
    </div>
  </div>
  <div class="theme-card">
    <div class="theme-card__visual theme-card__visual--three" aria-hidden="true">
      <img class="theme-card__image" src="/images/research-agenda/theme-3.webp" alt="Theme 3 illustration">
    </div>
    <div class="theme-card__content">
      <div class="theme-card__index">Theme 3</div>
      <div class="theme-card__title">
        <span class="lang-zh">工艺物理嵌入的机器人加工与操作优化</span>
        <span class="lang-en">Process-Physics-Embedded Robotic Machining and Manipulation</span>
      </div>
      <p class="theme-card__body">
        <span class="lang-zh">将机器人加工与操作视为多体、多场、多尺度、强耦合的非线性动力系统，研究柔顺性、惯量、接触力、切削载荷与瞬态动态如何共同决定质量形成、稳定性与失稳边界，并进一步探索刚度驱动的“硬”加工范式与生命启发的自适应“软”加工范式能否在统一的工艺物理与形态智能框架下得到联系。</span>
        <span class="lang-en">I study robotic machining and manipulation as coupled nonlinear dynamical systems in which compliance, inertia, contact force, cutting load, and transient dynamics jointly govern quality formation, stability, and failure boundaries. A longer-term question is whether the stiffness-driven hard paradigm of robotic machining and softer bio-inspired paradigms of adaptive material removal can be linked within a unified framework of process physics, morphology, and embedded intelligence.</span>
      </p>
    </div>
  </div>
</div>

---

## <span class="lang-zh">Career</span><span class="lang-en">Career</span>

<div class="career-card">
  <div class="career-card__text">
    <div class="lang-zh">
      <p><strong>上海交通大学溥渊未来技术学院</strong>：讲师（2025.07 - 至今）</p>
    </div>

    <div class="lang-en">
      <p><strong>Global Institute of Future Technology, Shanghai Jiao Tong University</strong>: Lecturer (Jul. 2025 - present)</p>
    </div>
  </div>
  <img class="career-card__logo" src="/images/education/gift-puyuan.png" alt="Puyuan logo">
</div>

---

## <span class="lang-zh">荣誉与奖励</span><span class="lang-en">Awards and Honors</span>

<div class="lang-zh" markdown="1">
**学术荣誉**

- 博士研究生国家奖学金（2025）
- 上海市优秀毕业生（2025）
- 入选上海交通大学博士生“学术领航计划”（全校 36 人，2024）
- 上海交通大学优秀团干部（2024）
- 上海交通大学优秀学生干部（2024）
- 俞黎明奖学金，上海交通大学密西根学院（2024）
- 学生发展奖学金，上海交通大学密西根学院（2022，2023，2024）
- 上海交通大学三好学生（2023）
- 大连理工大学优秀毕业生（2020）
- 大连理工大学文体活动奖学金（2017，2018，2019）
- 大连理工大学精神文明奖学金（2017，2018，2019）
- 大连理工大学学业优秀奖学金（2016，2017）

**竞赛与社会实践奖励**

- 中国国际大学生创新大赛（2025，总决赛）金奖（指导教师，2025.08）
- 中国国际大学生创新大赛（2025，上海赛区）铜奖（2025.08）
- 上海交通大学学生社会实践一等奖、优秀指导教师（2024.12）
- 上海交通大学“盛宣怀杯”第二十五届创新创业大赛银奖（2024.09）
- 上海交通大学密西根学院“盛相杯”创新大赛二等奖（2024.05）
- 中国国际大学生创新大赛全国总决赛银奖（2023.12）
- 上海市“知行杯”大学生社会实践大赛一等奖（2023.11）
- 第九届中国国际大学生“互联网+”创新创业大赛上海赛区金奖（2023.10）
- 第十二届认证杯中国数学建模网络挑战赛二等奖（2019.05）
- 第八届亚太地区大学生数学建模竞赛二等奖（2019.01）
- 第三届“临潮杯”国际华语辩论邀请赛东北赛区冠军（2018.09）
- 大连市“驭衡杯”辩论赛冠军（2017.12）

注：未特别注明“指导教师”的竞赛奖项，均为本人作为参赛者获得。
</div>

<div class="lang-en" markdown="1">
**Academic Honors**

- National Scholarship for Ph.D. Students (2025)
- Outstanding Graduate of Shanghai (2025)
- Selected for the SJTU Doctoral Helmsman Program (36 university-wide, 2024)
- Outstanding Youth League Cadre, Shanghai Jiao Tong University (2024)
- Outstanding Student Cadre, Shanghai Jiao Tong University (2024)
- Yu Liming Scholarship, UM-SJTU Joint Institute (2024)
- Student Development Scholarship, UM-SJTU Joint Institute (2022, 2023, 2024)
- SJTU Merit Student (2023)
- Outstanding Graduate, Dalian University of Technology (2020)
- Scholarship for Cultural and Sports Activities, Dalian University of Technology (2017, 2018, 2019)
- Scholarship for Spiritual Civilization, Dalian University of Technology (2017, 2018, 2019)
- Academic Excellence Scholarship, Dalian University of Technology (2016, 2017)

**Competitions and Distinctions**

- Gold Award (Advisor), China International College Students' Innovation Competition, National Finals (2025)
- Bronze Award, China International College Students' Innovation Competition, Shanghai Division (2025)
- First Prize and Outstanding Advisor, SJTU Student Social Practice (2024)
- Silver Award, SJTU 25th Sheng Xuanhuai Innovation and Entrepreneurship Competition (2024)
- Second Prize, UM-SJTU Joint Institute Sheng Xiang Innovation Competition (2024)
- Silver Award, China International College Students' Innovation Competition, National Finals (2023)
- First Prize, Shanghai Zhixing Cup Social Practice Competition (2023)
- Gold Award, 9th China International College Students' "Internet+" Innovation and Entrepreneurship Competition, Shanghai Division (2023)
- Second Prize, 12th Certification Cup China Mathematical Contest in Modeling Challenge (2019)
- Second Prize, 8th Asia-Pacific Mathematical Contest in Modeling (2019)
- Champion, 3rd Linchao Cup International Chinese Debate Invitational, Northeast China Region (2018)
- Champion, Dalian Yuheng Cup Debate Tournament (2017)

</div>
