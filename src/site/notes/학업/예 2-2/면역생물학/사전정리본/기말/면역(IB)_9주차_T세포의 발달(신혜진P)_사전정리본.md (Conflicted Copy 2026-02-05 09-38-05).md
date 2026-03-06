---
{"dg-publish":true,"permalink":"//2-2////ib-9-t-p-md-conflicted-copy-2026-02-05-09-38-05/"}
---

<script>
MathJax = {
  tex: {
    inlineMath: [[',
    displayMath: [['$', '$'], ['\\[', '\\]'\|'$', '$'], ['\\[', '\\]']],
    processEscapes: true,
  },
  svg: {
    fontCache: 'global'
  }
};
</script>
<script type="text/javascript" id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-svg.js">
</script>

>[!quote] 공지
>본 자료의 저작권은 KAISTUDY에 있습니다.

---

> [!abstract]- 강의 요약: T세포의 발달 (T Cell Development)
>
> 이번 강의는 **Thymus**에 입학한 전구세포가 엄격한 **Selection**을 거쳐 정예 T세포로 졸업하는 과정을 다룹니다. 크게 **초기 발달(DN) -> 선택(DP) -> 계통 결정(SP) -> 졸업**의 흐름입니다.
>
> 1.  **Early Development (입학 및 진로 결정)**
>     * **장소:** Bone Marrow에서 온 전구세포가 **흉선(Thymus)**의 피질(Cortex)로 진입.
>     * **Notch 신호:** T세포가 되기 위한 필수 신호. (Notch1 없으면 B세포 됨).
>     * **DN 단계 (CD4-CD8-):** **CD44**와 **CD25** 마커 변화(DN1→DN2→DN3→DN4)를 통해 구분하며, **DN3** 단계에서 **$\beta$-Selection**을 통해 첫 번째 관문을 통과함.
>
> 2.  **$\beta$-Selection & Proliferation (중간 점검)**
>     * **Pre-TCR:** 기능적인 $\beta$ 사슬이 만들어졌는지 **Pre-T$\alpha$**와 결합해 확인.
>     * **결과:** 통과 시 **Allelic Exclusion**($\beta$ 유전자 재배열 중단), **대량 증식**, CD4/CD8 발현(DP 진입).
>
> 3.  **Selection Processes (졸업 시험: 98% 탈락)**
>     * **Positive Selection (Cortex):** **cTEC**이 제시하는 MHC를 **'적당히(Low affinity)'** 인식하면 생존. -> **MHC Restriction** 획득. (실패 시 Death by Neglect).
>     * **Negative Selection (Medulla):** **mTEC/DC**가 제시하는 자기 항원(Self-Ag)을 **'너무 세게(High affinity)'** 인식하면 제거. -> **Self-Tolerance** 획득.
>     * **Paradox 해결:** **Thymoproteasome($beta$ 5t)**이 피질에서 독특한 펩타이드를 만들어 양성 선택을 도움.
>
> 4.  **Lineage Commitment & Exit (진로 선택 및 졸업)**
>     * **CD4 vs CD8:** **Kinetic Signaling Model**에 따라 신호가 지속되면(Continuous) **CD4**, 끊기면(Interrupted) **CD8**이 됨. (전사인자 **ThPOK** vs **Runx3**의 길항 작용).
>     * **Exit:** **S1P-S1PR1** 상호작용을 통해 성숙한 T세포가 혈관으로 탈출.

> [!example]- 핵심 키워드 정리 (Key Terms & Concepts)
>
> ### 1. DN Stages & Checkpoints (족보)
> * **Notch1:** T세포 운명 결정의 핵심 (Notch on = T cell, Notch off = B cell).
> * **DN Markers:**
>     * **DN1:** `c-Kit++`, `CD44+`, `CD25-`
>     * **DN2:** `c-Kit++`, `CD44+`, **`CD25+`** (TCR 재배열 시작, Commitment).
>     * **DN3:** `c-Kit+`, **`CD44-`**, `CD25+` (**$\beta$-Selection**, Pre-TCR).
>     * **DN4:** `c-Kit-`, `CD44-`, **`CD25-`** (Proliferation, DP 준비).
> * **$\beta$-Selection:** DN3 단계. Pre-TCR 형성 확인 -> **Allelic Exclusion** 유도 -> **RAG 일시 중단** 및 증식.
>
> ### 2. Positive & Negative Selection (핵심 기전)
> * **Goldilocks Hypothesis:** 결합력이 너무 약해도(Neglect), 너무 강해도(Negative) 죽고, **적당해야(Positive)** 산다.
> * **MHC Restriction:** 흉선 환경(Thymus Stroma)에 의해 학습됨. (Chimera 실험: F1 골수 -> Parent B 흉선 이식 시 B형 MHC만 인식).
> * **H-Y Transgenic Mouse:**
>     * 수컷(Male): H-Y 항원 있음 -> 고친화력 -> **Negative Selection (Deletion)**.
>     * 암컷(Female): H-Y 항원 없음 -> 적당한 친화력 -> **Positive Selection (CD8 SP 생존)**.
> * **THEMIS:** 양성 선택 시 TCR 신호 감도 조절(Dampening by SHP-1).
> * **AIRE (AutoImmune Regulator):** 수질(mTEC)에서 췌장, 갑상선 등 **TSA(조직 특이 항원)**를 강제 발현시켜 자가반응성 T세포 제거. (결핍 시 자가면역질환).
> * **Thymoproteasome ($\beta$5t):** cTEC 특이적. 저친화력 펩타이드 생성 -> 양성 선택 유도.
>
> ### 3. Lineage Commitment (CD4 vs CD8)
> * **Kinetic Signaling Model (Singer):**
>     * MHC II 결합 -> CD8 down -> 신호 **지속(Continuous)** -> **CD4** 분화 (**ThPOK**).
>     * MHC I 결합 -> CD8 down -> 신호 **중단(Disrupted)** -> IL-7 신호 -> **CD8** 재발현 및 분화 (**Runx3**).
>
> ### 4. Graduation (Exit)
> * **S1PR1 & S1P:** 흉선 성숙 완료 시 **Foxo1 -> KLF2 -> S1PR1** 발현. 혈액 내 높은 S1P 농도를 따라 흉선 탈출(Egress).

---

> [!NOTE] Pages 1-5: T세포 발달의 개요와 흉선의 해부학적 구조
> 자, 먼저 숲을 보고 나무를 봅시다. T세포가 어디서 태어나서 어디로 가는지, 그 '학교'의 구조가 어떻게 생겨먹었는지부터 잡고 갑니다.
>
> > [!INFO] PAGE 2: 흉선의 퇴화 (Involution)
> > 2페이지 상단의 그림을 보세요. 아기 때(기어갈 때)는 흉선이 빵빵하죠? 그런데 나이 들수록(지팡이 짚을 때) 어떻게 됩니까? 쪼그라듭니다.
> > * **지방화(Fatty degeneration):** 나이가 들면 흉선 실질이 지방으로 대체되면서 T세포 생산 능력이 떨어집니다. 이게 노인 면역 저하의 원인 중 하나예요.
> > * **발달 타임라인:** 그림 아래쪽을 보면, **Bone Marrow(골수)**에서 온 전구세포가 **DN(Double Negative)** → **DP(Double Positive)** → **SP(Single Positive)** 단계로 성숙해가는 과정이 보이죠? 이 용어들, 오늘 지겹게 들을 거니 지금 눈에 익히세요.
>
> > [!INFO] PAGE 4: 흉선의 구조와 이동 경로 (Traffic)
> > 4페이지 그림 (a), (b), (c)를 같이 봅니다. T세포는 가만히 앉아서 크는 게 아니라, 흉선 안을 '이동'하면서 교육받습니다.
> > * **구조 (바깥 -> 안쪽):**
> >     1.  **Capsule (피막):** 껍데기.
> >     2.  **Subcapsular Cortex (피막하 피질):** 전구세포가 처음 들어와서 증식하는 곳.
> >     3.  **Cortex (피질/겉질):** 그림 (a)에서 진하게 염색된 부분. 여기서 **DN3, DN4, DP** 단계가 진행됩니다. **Positive Selection(양성선택)**의 주무대죠.
> >     4.  **Corticomedullary Junction:** 피질과 수질의 경계. 혈관(Blood vessel)이 여기로 들어옵니다. 전구세포도 여기로 들어오고, 다 큰 놈도 여기로 나갑니다.
> >     5.  **Medulla (수질/속질):** 그림 (a)에서 밝은 부분. **SP** 단계, **Negative Selection(음성선택)**이 일어납니다.
> > * **이동 경로 (화살표 보세요):** 혈관 타고 **CM Junction**으로 진입 -> **Subcapsular Cortex**로 이동 -> 다시 안쪽 **Cortex**로 진입 -> **Medulla** -> **Exit**. 이 동선을 기억해야 단계별 위치 문제를 맞춥니다.
>
> > [!INFO] PAGE 5: 흉선 상피세포 (Stroma)
> > T세포 혼자 크는 게 아닙니다. '선생님' 역할을 하는 상피세포들이 있어요.
> > * **cTECs (Cortical Thymic Epithelial Cells):** 피질에 있는 선생님. **Positive Selection** 담당.
> > * **mTECs (Medullary Thymic Epithelial Cells):** 수질에 있는 선생님. **Negative Selection** 담당.
> > * 이 세포들이 뭘 발현하느냐에 따라 T세포의 운명이 갈립니다.

> [!NOTE] Pages 6-9: 초기 발달과 Notch 신호 (운명의 갈림길)
> 흉선에 들어왔다고 무조건 T세포가 되는 게 아닙니다. "너 T세포 할래, B세포 할래?"를 결정하는 결정적인 신호가 있습니다. 여기서 **'야마(족보)'** 나옵니다.
>
> > [!IMPORTANT] PAGE 7: Notch Signaling (족보 포인트)
> > 7페이지 그림에 **"NOTCH"**라고 대문짝만하게 박혀 있고 **별표(야마)** 쳐져 있죠? 이거 무조건 나옵니다.
> > * **핵심:** 조혈모세포(HSC)가 흉선에 왔을 때, **Notch 신호**를 받아야만 T세포가 됩니다.
> > * **실험 증거 (텍스트 보세요):**
> >     1.  **Notch1 과발현(Overexpression):** 골수(Bone Marrow)에서도 T세포가 생겨버림 (원래는 B세포가 생겨야 함).
> >     2.  **Notch1 제거(Knockout):** 흉선(Thymus)인데도 T세포 대신 B세포가 생겨버림.
> > * **결론:** **"Notch = T cell lineage commitment"**. Notch가 있으면 T세포, 없으면 B세포입니다. (그림에서 B세포 쪽으로 가는 화살표에는 Notch 신호가 없는 걸 확인하세요!)
>
> > [!TIP] 💡 PAGE 8: OP9-DL1 실험 데이터 해석 (기출)
> > 이 데이터 해석하는 문제 자주 나옵니다. 8페이지 그림 뜯어봅시다.
> > * **실험 셋업:**
> >     * **OP9 세포:** 기질세포(Stromal cell).
> >     * **DL1 (Delta-like 1):** **Notch의 Ligand(리간드)**입니다. 즉, DL1이 있어야 Notch 신호를 줄 수 있습니다.
> > * **결과 그래프 (FACS Plot):**
> >     * **왼쪽 (Notch1 -/-):** Notch 수용체를 없앤 쥐. 흉선에 넣었는데도 **B세포(CD19+)**만 잔뜩 생깁니다. T세포는 안 생겨요.
> >     * **오른쪽 (Control):** 정상. T세포(Thy1+)가 잘 생깁니다.
> >     * **아래쪽 (OP9-DL1 배양):** 배양 접시에 **DL1(Notch 리간드)**을 깔아줬더니 줄기세포가 **DN1 -> DN2 -> DN3**로 쑥쑥 큽니다. (그림의 숫자 44, 25는 CD44, CD25 마커를 뜻함. 뒤에서 자세히 다룸).
> > * **한마디로:** 흉선 환경(Notch Ligand)이 없으면 T세포는 절대 못 만든다!

> [!NOTE] Pages 10-14: DN 단계의 세분화와 TCR 운명 결정 (Race)
> 자, 이제 **DN(Double Negative)** 단계를 현미경으로 들여다볼 시간입니다.
> 10페이지 그림과 11페이지 표, **이거 시험에 나옵니다.** 멍하니 "DN이구나" 하고 넘어가는 순간 유급입니다.
> DN 세포는 표면에 **CD4**도 없고 **CD8**도 없죠? 그럼 뭘로 구분하냐? 바로 **CD44**와 **CD25**입니다. 이 마커 변화를 외워야 합니다.
>
> > [!IMPORTANT] PAGE 10-11: DN1 ~ DN4 단계별 마커 (족보 테이블)
> > 11페이지 표를 보세요. **c-Kit (CD117)**, **CD44**, **CD25** 이 세 가지 마커의 변화 흐름을 잡아야 합니다.
> >
> > * **DN1 (Early):**
> >     * **마커:** `c-Kit++`, `CD44+`, `CD25-`
> >     * **특징:** 아직 흉선으로 이사 오는 중이거나 막 도착한 상태입니다. 아직 T세포로 완전히 결정되지 않아서(Multipotent), NK세포나 수지상세포(DC)로 빠질 수도 있는 시기입니다.
> >
> > * **DN2 (Commitment & Gene Rearrangement):**
> >     * **마커:** `c-Kit++`, `CD44+`, `CD25+` (**CD25가 양성으로 바뀜!**)
> >     * **핵심:** 여기서 **TCR 유전자 재배열($\gamma, \delta, \beta$)**이 시작됩니다. 그리고 7페이지에서 봤던 **Notch 신호**가 가장 강력하게 작용해서 "나는 이제 죽어도 T세포다"라고 **Commitment(계통 결정)**를 박는 시기입니다.
> >
> > * **DN3 ($\beta$-Selection Checkpoint):**
> >     * **마커:** `c-Kit+`, `CD44-`, `CD25+` (**CD44가 음성으로 바뀜!**)
> >     * **핵심:** 가장 중요합니다. 여기서 **$\beta$-selection**이 일어납니다. 즉, "TCR $\beta$ 사슬을 제대로 만들었니?" 검사하는 단계입니다. 통과 못 하면? 죽습니다(Apoptosis). Pre-TCR이 발현되는 시기이기도 하죠.
> >
> > * **DN4 (Pre-DP):**
> >     * **마커:** `c-Kit low/-`, `CD44-`, `CD25-` (**둘 다 음성!**)
> >     * **특징:** $\beta$-selection 통과했으니 기분 좋아서 미친듯이 **증식(Proliferation)**합니다. 그리고 이제 **$\alpha$ 사슬 재배열**을 준비하면서 **DP(Double Positive)** 단계로 넘어갑니다.
>
> > [!INFO] PAGE 13: TCR의 구조 ($\alpha\beta$ vs $\gamma\delta$)
> > 그림을 보세요. T세포는 두 종류의 수용체 중 하나를 가집니다.
> > * **$\alpha\beta$ TCR:** 우리 몸 T세포의 95% 이상. 적응면역의 주역이죠.
> > * **$\gamma\delta$ TCR:** 5% 미만. 주로 점막(Mucosa)이나 피부에 박혀서 선천면역처럼 작용합니다.
> > * 구조적으로 둘 다 **V(Variable)** 영역과 **C(Constant)** 영역이 있고, 세포막에 박혀 있죠? 옆에 **CD3 복합체($\epsilon, \delta, \gamma, \zeta$)**가 붙어있는 것도 똑같습니다. (CD3 없으면 신호 전달 못 합니다.)
>
> > [!TIP] 💡 PAGE 14: 확률 게임 (The Race Model)
> > 14페이지 텍스트를 씹어먹어 봅시다. 왜 $\alpha\beta$ T세포가 압도적으로 많을까요?
> > **"확률(Probability)"** 싸움입니다.
> > * **규칙:** DN2~DN3 단계에서 $\gamma, \delta, \beta$ 유전자 재배열이 동시에 시작됩니다(경주 시작!).
> > * **$\gamma\delta$ T세포가 되려면:** $\gamma$ 사슬과 $\delta$ 사슬 **두 개가 모두** 성공적으로 재배열되어야 합니다. (이벤트 2개 필요)
> > * **$\alpha\beta$ (정확히는 Pre-TCR) T세포가 되려면:** $\beta$ 사슬 **하나만** 성공하면 일단 멈추고($\beta$-selection), 증식한 뒤에 나중에 $\alpha$를 만듭니다. (이벤트 1개 필요)
> > * **결론:** 1개만 성공하면 되는 $\beta$ 쪽이 2개를 다 성공해야 하는 $\gamma\delta$보다 확률적으로 훨씬 유리합니다. 그래서 3배 이상 $\alpha\beta$ 쪽으로 많이 가는 겁니다.

> [!NOTE] Pages 15-20: $\gamma\delta$ T세포와 운명의 관문 ($\beta$-Selection)
> 자, 확률 게임에서 밀린 **$\gamma\delta$ T세포** 이야기 잠깐 하고, T세포 발달사에서 가장 중요한 **$\beta$-Selection**으로 넘어갑니다. 집중하세요.
>
> > [!INFO] PAGE 15: 태아 시기의 파동 (Waves)
> > 15페이지 그래프 보세요. X축이 **태아 발생일(Days of gestation)**입니다.
> > * **14~15일경:** 까만 선(**$\gamma\delta$ Thymocytes**)이 먼저 확 치솟습니다. 태아 때는 $\gamma\delta$가 먼저 만들어져요. 왜? 만들기 쉬우니까요. (단순하잖아)
> > * **출생(Birth) 이후:** 파란 선(**$\alpha\beta$ Thymocytes**)이 역전해서 압도적으로 많아집니다. 성인의 T세포 중 $\gamma\delta$는 **0.5%**밖에 안 됩니다.
>
> > [!INFO] PAGE 16: $\gamma\delta$ T세포의 마이웨이
> > 이놈들은 $\alpha\beta$와는 가는 길이 다릅니다. **"DP(Double Positive) 단계"를 안 거칩니다.**
> > * **특징 3가지 (외우세요):**
> >     1.  흉선을 나갈 때 **DN(CD4-CD8-)** 상태로 나갑니다. (쿨하게 나감)
> >     2.  **MHC 제한**이 없습니다. 이상한 항원(Lipid 등)을 인식해요.
> >     3.  주로 **점막(Mucosa)이나 피부(Skin)**로 가서 박혀 있습니다. 선천면역(Innate)처럼 최전방 방어선 역할을 하죠.
>
> > [!IMPORTANT] PAGE 18-19: $\beta$-Selection (생사가 걸린 검문소)
> > 18페이지 그림에 빨간 박스로 **$\beta$-selection** 표시돼 있죠? 별표 다섯 개 치세요. DN3 단계에서 일어나는 가장 결정적인 사건입니다.
> > * **상황:** $\beta$ 사슬 재배열을 끝냈습니다. 근데 이게 제대로 만들어졌는지 어떻게 알까요? 짝꿍인 $\alpha$ 사슬은 아직 안 만들었는데?
> > * **해결책 (Pre-TCR):** 그래서 **Pre-T$\alpha$**라는 가짜(Surrogate) $\alpha$ 사슬을 붙여봅니다. 이게 $\beta$ 사슬이랑 잘 붙어서 세포막에 뜨면 "합격" 신호가 터집니다.
> > * **신호의 결과 (4가지 기전 - 시험 나옵니다):**
> >     1.  **Stop $\beta$-rearrangement (Allelic Exclusion):** "하나 성공했으면 됐어. 다른 쪽 염색체 $\beta$ 유전자는 건드리지 마." (단일 특이성 보장)
> >     2.  **Proliferation (증식):** "성공한 놈이니까 복제해!" 세포 수가 폭발적으로 늘어납니다. (DN4 단계)
> >     3.  **Start $\alpha$-rearrangement:** "자, 이제 진짜 짝꿍($\alpha$) 만들자."
> >     4.  **Expression of CD4/CD8:** "이제 옷 입자." DP 단계로 넘어갑니다.
>
> > [!TIP] 💡 PAGE 20: RAG 발현의 파동 (기출)
> > 20페이지 아래쪽 그래프 보세요. **RAG(Recombination Activating Gene)** 효소 수치가 오르락내리락하죠?
> > * **1차 피크 (DN2~3):** $\beta$ 사슬 자르느라 RAG가 높습니다.
> > * **급격한 감소 (DN3~4):** $\beta$-selection 통과 후 **증식(Proliferation)**할 때는 RAG를 끕니다. (세포 분열 중에 DNA 자르면 큰일 나니까요. 이거 중요합니다!)
> > * **2차 피크 (DP):** 증식 끝나고 $\alpha$ 사슬 자르려니 다시 RAG가 올라갑니다. 이 흐름을 이해해야 그래프 문제 풉니다.

> [!NOTE] Pages 21-26: 양성 선택과 음성 선택의 서막 (지옥의 훈련소)
> 자, 유전자 재배열도 끝났고 $\beta$-selection도 통과해서 DP(Double Positive)가 됐습니다. 이제부터 진짜 '고시'가 시작됩니다.
> 23페이지 수치를 보세요. **98%가 죽습니다.** 단 2%만 살아남는 지옥의 훈련소, 그 원리를 파헤쳐 봅시다.
>
> > [!INFO] PAGE 22: 노벨상 수상자 (Doherty & Zinkernagel)
> > 이 아저씨들 얼굴 보고 지나가지 마세요. 이분들이 **MHC Restriction(MHC 제한)** 개념을 발견해서 노벨상 탔습니다.
> > * **핵심 개념 (외우세요):**
> >     * **Positive Selection (양성 선택):** 자기 MHC를 **'적당히(Low affinity)'** 인식할 줄 아는 놈만 살립니다. -> 결과: **MHC Restriction** 획득.
> >     * **Negative Selection (음성 선택):** 자기 MHC+자기 펩타이드에 **'너무 세게(High affinity)'** 반응하는 놈은 죽입니다. -> 결과: **Self-Tolerance(자기 관용)** 획득.
> > * 즉, **"너무 무관심해도 죽고(Neglect), 너무 집착해도 죽는다(Negative)."** 적당한 놈만 사는 겁니다. (Goldilocks hypothesis)
>
> > [!IMPORTANT] PAGE 25: MHC Restriction 증명 실험 (야마/기출)
> > **이 실험 100% 시험 나옵니다.** 별표 다섯 개 치세요. 방사선 조사 쥐(Chimera) 실험입니다.
> > 논리를 단계별로 따라오세요.
> > 1.  **준비물:**
> >     * **(A x B) F1 쥐:** 유전적으로 MHC A형과 B형을 둘 다 가짐.
> >     * **Strain B 쥐:** MHC B형만 가짐. (흉선을 제공할 대리모)
> > 2.  **실험 과정:**
> >     * Strain B 쥐에 방사선을 쏴서 자기 면역세포를 다 죽이고, **(A x B) F1의 골수(Stem cells)**를 이식합니다.
> >     * 그럼 F1 유전자를 가진 T세포가 **Strain B의 흉선(Thymus)**에서 교육받고 자라겠죠?
> > 3.  **결과 (핵심):**
> >     * 다 큰 T세포를 꺼내서 바이러스 감염된 세포를 죽이게 했더니, **Strain B 세포는 죽이는데(Killing), Strain A 세포는 못 죽입니다(No killing).**
> > 4.  **결론 (Interpretation):**
> >     * T세포의 **유전자**는 A, B 둘 다 가지고 있었지만, **흉선 학교가 B형**이라서 **"B형 MHC 보는 법"만 배웠다**는 겁니다.
> >     * 즉, **"MHC Restriction은 유전자가 아니라 흉선 환경(Thymus Environment)에 의해 학습된다."** 이게 정답입니다.
>
> > [!INFO] PAGE 26: 선택의 장소 (Cortex vs Medulla)
> > 그림의 위치와 비율을 보세요.
> > * **Cortex (피질):** 여기서 **Positive Selection**이 주로 일어납니다. 담당 교관은 **cTEC**입니다.
> > * **Death by Neglect (90~96%):** 그림 오른쪽 보세요. 대부분의 세포는 자기 MHC를 아예 인식 못 해서 여기서 그냥 **굶어 죽습니다(Apoptosis)**. 억울하게 죽는 게 아니라 무능해서 죽는 겁니다.
> > * **Medulla (수질):** 살아남은 애들이 여기로 와서 **Negative Selection**을 받습니다. 담당 교관은 **mTEC, DC(수지상세포)**입니다. 여기서 자기 몸 공격할 미친 놈들을 걸러냅니다.

> [!NOTE] Pages 27-33: MHC 제한과 H-Y 형질전환 마우스 실험 (실험 데이터 해석의 꽃)
> 자, 앞서 배운 MHC Restriction과 Negative Selection 이론을 실제로 증명한 전설적인 실험이 나옵니다.
> **H-Y Transgenic Mouse 실험**은 면역학 실험 데이터 해석 문제의 '조상님'입니다. FACS(유세포 분석) 데이터를 읽을 줄 모르면 시험장에 들어갈 생각도 하지 마세요.
>
> > [!INFO] PAGE 28-29: 친화력 모델 (Goldilocks Hypothesis)
> > 28페이지 그림을 봅시다. T세포의 운명은 **"TCR이 자기 MHC+자기 펩타이드를 얼마나 세게 잡느냐(Affinity)"**에 달려 있습니다.
> > * **No Interaction (무반응):** 90~96%가 해당됩니다. 아예 인식을 못 하니 쓸모가 없죠? **Death by Neglect (방치되어 사망)**.
> > * **High Affinity (너무 강함):** 자기 몸을 공격할 놈들입니다. 위험하죠? **Negative Selection (음성 선택)**으로 제거(Apoptosis)됩니다.
> > * **Low/Intermediate Affinity (적당함):** "어? 이거 내 MHC네?" 하고 살짝 건드리는 정도. 이놈들만 **Positive Selection (양성 선택)**으로 살아남아 **SP(Single Positive)**가 됩니다.
> > * **핵심:** 너무 차가워도 안 되고, 너무 뜨거워도 안 됩니다. 딱 적당해야 합니다.
>
> > [!IMPORTANT] PAGE 30: H-Y Transgenic Mouse 실험 셋업 (족보)
> > 30페이지 실험 설계를 뜯어봅시다. 조건이 복잡하니 집중하세요.
> > * **H-Y 항원:** 수컷(Male)에만 있는 항원입니다. (Y염색체 유래). 즉, **수컷에게는 'Self'**이고, **암컷에게는 'None'**입니다.
> > * **Transgenic TCR:** 연구자가 조작해서 넣어준 TCR입니다. 이 TCR은 **H-Y 항원**을 **H-2D^b (MHC Class I)**에 얹어서 제시할 때만 알아봅니다.
> > * **실험군 4가지:**
> >     1.  **Female H2-D^b:** H-Y 항원 없음 (적당한 결합 예상 -> 양성 선택).
> >     2.  **Male H2-D^b:** H-Y 항원 있음 (너무 강한 결합 예상 -> 음성 선택).
> >     3.  **Female H2-D^d:** MHC 종류가 다름 (결합 안 됨 -> 무시).
>
> > [!TIP] 💡 PAGE 31-33: FACS 데이터 해석 (기출 포인트)
> > 33페이지 FACS Plot을 보세요. X축은 **CD8**, Y축은 **CD4**입니다. 이 그림 해석하는 게 시험 문제입니다.
> >
> > * **1. Female H2-D^b (가운데 그림):**
> >     * **상황:** H-Y 항원이 없으므로 TCR이 '적당히' MHC만 인식합니다.
> >     * **결과:** **CD8+ SP 세포(오른쪽 아래, 37%)**가 뙇 하고 존재합니다.
> >     * **해석:** **Positive Selection**이 정상적으로 일어나서 CD8 T세포로 분화했습니다. (MHC Class I은 CD8을 만드니까요).
> >
> > * **2. Male H2-D^b (왼쪽 그림):**
> >     * **상황:** 수컷이라 H-Y 항원이 쫙 깔려 있습니다. TCR이 자기 항원(H-Y)을 '너무 세게' 뭅니다.
> >     * **결과:** CD8+ SP가 거의 없고(2%), **CD8low** 상태로 찌그러져 있거나 죽었습니다.
> >     * **해석:** **Negative Selection (Deletion)**이 일어나서 다 죽어나간 겁니다. 자기 반응성 세포를 없애는 과정이죠.
> >
> > * **3. Female H2-D^d (오른쪽 그림):**
> >     * **상황:** MHC 유전자가 **D^d**입니다. 이 TCR은 **D^b**만 좋아합니다. 짝이 안 맞죠?
> >     * **결과:** SP 세포가 아예 없습니다(0~3%). DP 단계(오른쪽 위)에만 머물러 있죠?
> >     * **해석:** 인식을 못 하니 양성 선택을 못 받아서 **Death by Neglect** 당한 겁니다. **"MHC Restriction"**을 증명하는 결과죠.
> >
> > * **결론:** 이 세 가지 그림을 보고 "양성 선택", "음성 선택", "MHC 제한"을 각각 매칭할 수 있어야 합니다.


> [!NOTE] Pages 34-37: 양성 선택의 분자적 기전 (THEMIS의 등장)
> 단순히 "적당히 결합하면 산다"로 끝내면 의대 수업이 아니죠. 그 신호가 세포 안에서 구체적으로 어떻게 전달되는지, **THEMIS**라는 단백질을 중심으로 파고듭니다.
>
> > [!INFO] PAGE 35: Death by Neglect (무시당한 자의 최후)
> > 35페이지 텍스트 보세요. 양성 선택(Positive Selection)을 통과하지 못한 세포들은 **3~4일** 안에 생존 신호를 못 받아서 **Apoptosis(세포자멸사)**로 죽습니다.
> > * 왜 이렇게 많이 죽일까요? (이유 2가지)
> >     1.  **Cluttering 방지:** 아무것도 인식 못 하는 멍청한 세포가 몸을 돌아다니며 공간만 차지하는 걸 막기 위함.
> >     2.  **확률 높이기:** 진짜 항원을 만날 확률이 있는 놈들만 남겨놔야 면역 효율이 올라가니까요.
>
> > [!TIP] 💡 PAGE 37: THEMIS Signaling Pathway (신상 족보)
> > 37페이지 그림, **THEMIS** 박스에 별표(야마) 쳐져 있죠? 이게 비교적 최근에 밝혀진 **가슴샘 세포 특이적 신호 분자**입니다.
> > * **위치:** 그림을 보면 **TCR 신호 전달 경로(Lck -> ZAP70 -> LAT)** 사이에 딱 끼어 있습니다.
> > * **작동 기전 (Mechanism):**
> >     * THEMIS는 **GRB-2**를 통해 **SHP-1 (Phosphatase, 인산분해효소)**을 끌고 옵니다.
> >     * **SHP-1**은 신호를 **끄는(Dampening)** 역할을 하죠.
> >     * **결과:** TCR 신호가 너무 강하지 않게 적절히 조절해서, 약한 신호(Low affinity)에서도 세포가 "어? 이거 양성 선택 신호네?"라고 알아먹고 생존하도록 돕습니다.
> > * **한마디로:** **"Positive Selection을 가능하게 하는 신호 튜너(Tuner)"**입니다. 이거 없으면 양성 선택이 안 됩니다.


> [!NOTE] Pages 38-46: 음성 선택과 AIRE (내 몸을 지키는 그림자)
> 이제 수질(Medulla)로 넘어왔습니다. 여기서 가장 중요한 건 **AIRE (AutoImmune Regulator)**입니다. 이건 면역학 전체를 통틀어 가장 중요한 개념 중 하나입니다.
>
> > [!IMPORTANT] PAGE 40: mTEC과 수지상세포의 협동
> > 40페이지 그림을 보세요. 음성 선택(Negative Selection)은 누가 시킵니까?
> > * **주연:** **mTEC (수질 가슴샘 상피세포)**.
> > * **조연:** **Dendritic Cell (수지상세포)**. mTEC이 만든 항원을 주워먹고 대신 제시해주기도 합니다.
> > * 이 과정이 실패하면? 자기 반응성 세포가 나가서 **자가면역질환(Autoimmune disease)**을 일으킵니다. 대표적인 예가 **제1형 당뇨병(T1D)**이죠.
>
> > [!TIP] 💡 PAGE 44-46: AIRE와 TSA (자가면역의 핵심 기전)
> > 44페이지 텍스트 보세요. 흉선(Thymus)은 심장도 아니고 췌장도 아닌데, 어떻게 심장이나 췌장 세포를 공격할 놈을 미리 걸러낼까요?
> > * **TSA (Tissue-Specific Antigens):** 인슐린(췌장), 티로글로불린(갑상선) 같은 특정 조직 항원들을 말합니다.
> > * **AIRE의 역할 (핵심):** **mTEC**에만 있는 **AIRE 단백질**이 이 TSA 유전자들을 흉선에서 강제로 발현시킵니다. 일종의 **"전신 항원 미리보기 서비스(Shadow)"**를 제공하는 거죠.
> > * **분자 기전 (46페이지 그림 상세):**
> >     * AIRE는 닫혀 있는(Silenced) 염색질에 접근해서 **RNA Polymerase**를 끌고 옵니다.
> >     * 그림에 **Ac(아세틸화), Me(메틸화)** 보이죠? 후성유전학적(Epigenetic) 조절을 통해 꽁꽁 숨겨진 유전자를 억지로 읽어내는 겁니다.
> > * **결론:** AIRE가 고장 나면? 흉선에서 인슐린을 못 보여줍니다. -> 인슐린 공격하는 T세포가 살아서 나갑니다. -> **당뇨병** 걸립니다. (APECED 증후군)


> [!NOTE] Pages 47-53: 흉선의 역설 (Paradox)과 해결책
> 여기서 아주 날카로운 질문이 나옵니다. "아니, 양성 선택할 때 자기 MHC랑 반응하는 놈을 살린다며? 근데 음성 선택 때는 자기 MHC랑 반응하는 놈을 죽인다며? 그럼 다 죽어야 하는 거 아냐?"
> 이 **Thymic Paradox**를 해결하는 기가 막힌 기전을 설명합니다.
>
> > [!INFO] PAGE 50: OT-I / TAP1 실험 (펩타이드가 다르다!)
> > 50페이지 실험을 보세요. 이 모순을 풀기 위한 실험입니다.
> > * **TAP1 KO 쥐:** 펩타이드 수송체가 고장 나서 MHC가 텅 비어 있습니다(Empty MHC). -> 세포 다 죽음 (Death by neglect).
> > * **Low affinity Peptide 추가:** 살짝만 붙는 펩타이드를 넣어줬더니 -> **생존 (Positive Selection)**.
> > * **High affinity Peptide 추가:** 꽉 붙는 펩타이드를 넣어줬더니 -> **사망 (Negative Selection)**.
> > * **결론:** 결국 **"펩타이드와의 결합 세기(Affinity)"**가 생사를 가릅니다.
>
> > [!IMPORTANT] PAGE 52-53: Thymoproteasome ($\beta$ 5t) - 비밀병기
> > 53페이지 그림이 그 해답의 결정타입니다. 피질 상피세포(cTEC)는 단백질을 자르는 가위가 다릅니다.
> > * **일반 세포:** 일반 프로테아좀을 씁니다.
> > * **cTEC (피질 세포):** **$\beta$5t**라는 특수 소단위체를 가진 **Thymoproteasome**을 씁니다.
> > * **기능:** 이 특수 가위는 단백질을 듬성듬성 잘라서 **'결합력이 약한(Low affinity)' 독특한 펩타이드**를 만듭니다.
> > * **해결:**
> >     1.  **Cortex:** cTEC이 만든 '약한 펩타이드'로 **양성 선택** (살살 달래서 살림).
> >     2.  **Medulla:** mTEC이나 DC가 만든 '진짜(강한) 펩타이드'로 **음성 선택** (세게 반응하는 놈 제거).
> >     * 이렇게 장소별로 **'메뉴(Peptide)'**를 다르게 해서 패러독스를 해결합니다.
> 
> >[!quote] 의문: PS에서 결합력이 약한 펩티드와 결합할 정도의 애면 NS에선 무조건 걸러지는거 아닌가?
> > - PS의 통과자는 **자기 MHC**를 인식할 수만 있으면 됨. 예컨대 자기 MHC+적당한 Peptide를 넣어버려서 **"약한 결합력"을 가지는 대신 MHC를 인식**할 수 있으면 통과.
> > - NS에서는 **결합력이 강한 Self peptide**를 제시해버려서, 조금이라도 자기 peptide와 결합할 수 있는 녀석은 모두 제거시키는거임.
> > - **결론: Peptide의 결합력 뿐만 아니라, 종류도 다르다**


> [!NOTE] Pages 54-60: 계통 결정 (Lineage Commitment) - CD4냐 CD8이냐
> DP 세포가 시험을 다 통과했습니다. 이제 옷을 갈아입어야죠. Helper(CD4)가 될지, Cytotoxic(CD8)이 될지 어떻게 정할까요?
>
> > [!IMPORTANT] PAGE 58: Kinetic Signaling Model (역동 신호 모델)
> > 58페이지 그림, **Singer 박사님** 이론입니다. 이게 최신 정설입니다. (야마!)
> > * **핵심:** "신호가 **끊기냐 지속되냐**가 운명을 가른다."
> > * **과정:**
> >     1.  양성 선택을 받으면 일단 **모든 DP 세포**는 **CD8 발현을 줄입니다(CD4+8lo)**.
> >     2.  **이때!**
> >         * **MHC II와 결합하던 놈:** CD4는 그대로 있으니 신호가 **계속(Continuous)** 들어옵니다 -> **CD4 T세포**가 됩니다.
> >         * **MHC I과 결합하던 놈:** CD8이 줄어드니까 신호가 **끊깁니다(Disrupted)**. 신호가 끊기면 **IL-7** 신호를 받아서 다시 CD8을 만들고 **CD8 T세포**가 됩니다.
> > * **요약:** 신호 지속(Continuous) = CD4, 신호 중단(Interrupted) + IL-7 구조 = CD8.
>
> > [!TIP] 💡 PAGE 59: Transcription Factor Switch (ThPOK vs Runx3)
> > 59페이지 그림의 분자 스위치를 외우세요. 서로 억제하는 관계입니다.
> > * **ThPOK:** **CD4**로 가는 열쇠. (T-Helper-POK).
> > * **Runx3:** **CD8**로 가는 열쇠.
> > * **기전:** ThPOK가 뜨면 Runx3를 누르고(CD4 됨), Runx3가 뜨면 ThPOK를 누릅니다(CD8 됨).


> [!NOTE] Pages 61-67: 졸업과 흉선 탈출 (Exit)
> 드디어 졸업입니다. 다 큰 T세포가 흉선을 떠나는 과정도 그냥 나가는 게 아닙니다.
>
> > [!INFO] PAGE 62: S1PR1과 탈출 기전
> > 62페이지 그림의 순서를 보세요.
> > 1.  **Foxo1 (전사인자)**이 활성화됩니다.
> > 2.  Foxo1이 **KLF2**를 켜고, KLF2가 **S1PR1 (스핑고신-1-인산 수용체)**을 발현시킵니다.
> > 3.  혈액 속에는 **S1P (Sphingosine-1-Phosphate)** 농도가 높습니다.
> > 4.  T세포의 S1PR1이 핏속의 S1P 냄새를 맡고 혈관으로 **Egress(탈출)**합니다.
> > * 참고: 흉선 안에서는 S1P 농도가 낮게 유지되어서 미성숙 세포가 못 나가게 막습니다.
>
> > [!INFO] PAGE 65-66: Treg (평화 유지군)
> > 마지막 보너스. 자기 반응성이 살짝 높은 애들(High affinity) 중 일부는 죽이지 않고 **Treg (조절 T세포)**로 스카우트합니다.
> > * **마커:** **FoxP3** (전사인자), **CD25**, **CD4**.
> > * **기능:** 사회(말초 조직)에 나가서 과도한 면역 반응을 억제합니다(Suppress). 사이토카인 뺏어먹기, 억제 물질 뿌리기 등으로 평화를 유지합니다.
, ',
    displayMath: [['$$', '$$'], ['\\[', '\\]']],
    processEscapes: true,
  },
  svg: {
    fontCache: 'global'
  }
};
</script>
<script type="text/javascript" id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-svg.js">
</script>

>[!quote] 공지
>본 자료의 저작권은 KAISTUDY에 있습니다.

---

> [!abstract]- 강의 요약: T세포의 발달 (T Cell Development)
>
> 이번 강의는 **Thymus**에 입학한 전구세포가 엄격한 **Selection**을 거쳐 정예 T세포로 졸업하는 과정을 다룹니다. 크게 **초기 발달(DN) -> 선택(DP) -> 계통 결정(SP) -> 졸업**의 흐름입니다.
>
> 1.  **Early Development (입학 및 진로 결정)**
>     * **장소:** Bone Marrow에서 온 전구세포가 **흉선(Thymus)**의 피질(Cortex)로 진입.
>     * **Notch 신호:** T세포가 되기 위한 필수 신호. (Notch1 없으면 B세포 됨).
>     * **DN 단계 (CD4-CD8-):** **CD44**와 **CD25** 마커 변화(DN1→DN2→DN3→DN4)를 통해 구분하며, **DN3** 단계에서 **$\beta$-Selection**을 통해 첫 번째 관문을 통과함.
>
> 2.  **$\beta$-Selection & Proliferation (중간 점검)**
>     * **Pre-TCR:** 기능적인 $\beta$ 사슬이 만들어졌는지 **Pre-T$\alpha$**와 결합해 확인.
>     * **결과:** 통과 시 **Allelic Exclusion**($\beta$ 유전자 재배열 중단), **대량 증식**, CD4/CD8 발현(DP 진입).
>
> 3.  **Selection Processes (졸업 시험: 98% 탈락)**
>     * **Positive Selection (Cortex):** **cTEC**이 제시하는 MHC를 **'적당히(Low affinity)'** 인식하면 생존. -> **MHC Restriction** 획득. (실패 시 Death by Neglect).
>     * **Negative Selection (Medulla):** **mTEC/DC**가 제시하는 자기 항원(Self-Ag)을 **'너무 세게(High affinity)'** 인식하면 제거. -> **Self-Tolerance** 획득.
>     * **Paradox 해결:** **Thymoproteasome($beta$ 5t)**이 피질에서 독특한 펩타이드를 만들어 양성 선택을 도움.
>
> 4.  **Lineage Commitment & Exit (진로 선택 및 졸업)**
>     * **CD4 vs CD8:** **Kinetic Signaling Model**에 따라 신호가 지속되면(Continuous) **CD4**, 끊기면(Interrupted) **CD8**이 됨. (전사인자 **ThPOK** vs **Runx3**의 길항 작용).
>     * **Exit:** **S1P-S1PR1** 상호작용을 통해 성숙한 T세포가 혈관으로 탈출.

> [!example]- 핵심 키워드 정리 (Key Terms & Concepts)
>
> ### 1. DN Stages & Checkpoints (족보)
> * **Notch1:** T세포 운명 결정의 핵심 (Notch on = T cell, Notch off = B cell).
> * **DN Markers:**
>     * **DN1:** `c-Kit++`, `CD44+`, `CD25-`
>     * **DN2:** `c-Kit++`, `CD44+`, **`CD25+`** (TCR 재배열 시작, Commitment).
>     * **DN3:** `c-Kit+`, **`CD44-`**, `CD25+` (**$\beta$-Selection**, Pre-TCR).
>     * **DN4:** `c-Kit-`, `CD44-`, **`CD25-`** (Proliferation, DP 준비).
> * **$\beta$-Selection:** DN3 단계. Pre-TCR 형성 확인 -> **Allelic Exclusion** 유도 -> **RAG 일시 중단** 및 증식.
>
> ### 2. Positive & Negative Selection (핵심 기전)
> * **Goldilocks Hypothesis:** 결합력이 너무 약해도(Neglect), 너무 강해도(Negative) 죽고, **적당해야(Positive)** 산다.
> * **MHC Restriction:** 흉선 환경(Thymus Stroma)에 의해 학습됨. (Chimera 실험: F1 골수 -> Parent B 흉선 이식 시 B형 MHC만 인식).
> * **H-Y Transgenic Mouse:**
>     * 수컷(Male): H-Y 항원 있음 -> 고친화력 -> **Negative Selection (Deletion)**.
>     * 암컷(Female): H-Y 항원 없음 -> 적당한 친화력 -> **Positive Selection (CD8 SP 생존)**.
> * **THEMIS:** 양성 선택 시 TCR 신호 감도 조절(Dampening by SHP-1).
> * **AIRE (AutoImmune Regulator):** 수질(mTEC)에서 췌장, 갑상선 등 **TSA(조직 특이 항원)**를 강제 발현시켜 자가반응성 T세포 제거. (결핍 시 자가면역질환).
> * **Thymoproteasome ($\beta$5t):** cTEC 특이적. 저친화력 펩타이드 생성 -> 양성 선택 유도.
>
> ### 3. Lineage Commitment (CD4 vs CD8)
> * **Kinetic Signaling Model (Singer):**
>     * MHC II 결합 -> CD8 down -> 신호 **지속(Continuous)** -> **CD4** 분화 (**ThPOK**).
>     * MHC I 결합 -> CD8 down -> 신호 **중단(Disrupted)** -> IL-7 신호 -> **CD8** 재발현 및 분화 (**Runx3**).
>
> ### 4. Graduation (Exit)
> * **S1PR1 & S1P:** 흉선 성숙 완료 시 **Foxo1 -> KLF2 -> S1PR1** 발현. 혈액 내 높은 S1P 농도를 따라 흉선 탈출(Egress).

---

> [!NOTE] Pages 1-5: T세포 발달의 개요와 흉선의 해부학적 구조
> 자, 먼저 숲을 보고 나무를 봅시다. T세포가 어디서 태어나서 어디로 가는지, 그 '학교'의 구조가 어떻게 생겨먹었는지부터 잡고 갑니다.
>
> > [!INFO] PAGE 2: 흉선의 퇴화 (Involution)
> > 2페이지 상단의 그림을 보세요. 아기 때(기어갈 때)는 흉선이 빵빵하죠? 그런데 나이 들수록(지팡이 짚을 때) 어떻게 됩니까? 쪼그라듭니다.
> > * **지방화(Fatty degeneration):** 나이가 들면 흉선 실질이 지방으로 대체되면서 T세포 생산 능력이 떨어집니다. 이게 노인 면역 저하의 원인 중 하나예요.
> > * **발달 타임라인:** 그림 아래쪽을 보면, **Bone Marrow(골수)**에서 온 전구세포가 **DN(Double Negative)** → **DP(Double Positive)** → **SP(Single Positive)** 단계로 성숙해가는 과정이 보이죠? 이 용어들, 오늘 지겹게 들을 거니 지금 눈에 익히세요.
>
> > [!INFO] PAGE 4: 흉선의 구조와 이동 경로 (Traffic)
> > 4페이지 그림 (a), (b), (c)를 같이 봅니다. T세포는 가만히 앉아서 크는 게 아니라, 흉선 안을 '이동'하면서 교육받습니다.
> > * **구조 (바깥 -> 안쪽):**
> >     1.  **Capsule (피막):** 껍데기.
> >     2.  **Subcapsular Cortex (피막하 피질):** 전구세포가 처음 들어와서 증식하는 곳.
> >     3.  **Cortex (피질/겉질):** 그림 (a)에서 진하게 염색된 부분. 여기서 **DN3, DN4, DP** 단계가 진행됩니다. **Positive Selection(양성선택)**의 주무대죠.
> >     4.  **Corticomedullary Junction:** 피질과 수질의 경계. 혈관(Blood vessel)이 여기로 들어옵니다. 전구세포도 여기로 들어오고, 다 큰 놈도 여기로 나갑니다.
> >     5.  **Medulla (수질/속질):** 그림 (a)에서 밝은 부분. **SP** 단계, **Negative Selection(음성선택)**이 일어납니다.
> > * **이동 경로 (화살표 보세요):** 혈관 타고 **CM Junction**으로 진입 -> **Subcapsular Cortex**로 이동 -> 다시 안쪽 **Cortex**로 진입 -> **Medulla** -> **Exit**. 이 동선을 기억해야 단계별 위치 문제를 맞춥니다.
>
> > [!INFO] PAGE 5: 흉선 상피세포 (Stroma)
> > T세포 혼자 크는 게 아닙니다. '선생님' 역할을 하는 상피세포들이 있어요.
> > * **cTECs (Cortical Thymic Epithelial Cells):** 피질에 있는 선생님. **Positive Selection** 담당.
> > * **mTECs (Medullary Thymic Epithelial Cells):** 수질에 있는 선생님. **Negative Selection** 담당.
> > * 이 세포들이 뭘 발현하느냐에 따라 T세포의 운명이 갈립니다.

> [!NOTE] Pages 6-9: 초기 발달과 Notch 신호 (운명의 갈림길)
> 흉선에 들어왔다고 무조건 T세포가 되는 게 아닙니다. "너 T세포 할래, B세포 할래?"를 결정하는 결정적인 신호가 있습니다. 여기서 **'야마(족보)'** 나옵니다.
>
> > [!IMPORTANT] PAGE 7: Notch Signaling (족보 포인트)
> > 7페이지 그림에 **"NOTCH"**라고 대문짝만하게 박혀 있고 **별표(야마)** 쳐져 있죠? 이거 무조건 나옵니다.
> > * **핵심:** 조혈모세포(HSC)가 흉선에 왔을 때, **Notch 신호**를 받아야만 T세포가 됩니다.
> > * **실험 증거 (텍스트 보세요):**
> >     1.  **Notch1 과발현(Overexpression):** 골수(Bone Marrow)에서도 T세포가 생겨버림 (원래는 B세포가 생겨야 함).
> >     2.  **Notch1 제거(Knockout):** 흉선(Thymus)인데도 T세포 대신 B세포가 생겨버림.
> > * **결론:** **"Notch = T cell lineage commitment"**. Notch가 있으면 T세포, 없으면 B세포입니다. (그림에서 B세포 쪽으로 가는 화살표에는 Notch 신호가 없는 걸 확인하세요!)
>
> > [!TIP] 💡 PAGE 8: OP9-DL1 실험 데이터 해석 (기출)
> > 이 데이터 해석하는 문제 자주 나옵니다. 8페이지 그림 뜯어봅시다.
> > * **실험 셋업:**
> >     * **OP9 세포:** 기질세포(Stromal cell).
> >     * **DL1 (Delta-like 1):** **Notch의 Ligand(리간드)**입니다. 즉, DL1이 있어야 Notch 신호를 줄 수 있습니다.
> > * **결과 그래프 (FACS Plot):**
> >     * **왼쪽 (Notch1 -/-):** Notch 수용체를 없앤 쥐. 흉선에 넣었는데도 **B세포(CD19+)**만 잔뜩 생깁니다. T세포는 안 생겨요.
> >     * **오른쪽 (Control):** 정상. T세포(Thy1+)가 잘 생깁니다.
> >     * **아래쪽 (OP9-DL1 배양):** 배양 접시에 **DL1(Notch 리간드)**을 깔아줬더니 줄기세포가 **DN1 -> DN2 -> DN3**로 쑥쑥 큽니다. (그림의 숫자 44, 25는 CD44, CD25 마커를 뜻함. 뒤에서 자세히 다룸).
> > * **한마디로:** 흉선 환경(Notch Ligand)이 없으면 T세포는 절대 못 만든다!

> [!NOTE] Pages 10-14: DN 단계의 세분화와 TCR 운명 결정 (Race)
> 자, 이제 **DN(Double Negative)** 단계를 현미경으로 들여다볼 시간입니다.
> 10페이지 그림과 11페이지 표, **이거 시험에 나옵니다.** 멍하니 "DN이구나" 하고 넘어가는 순간 유급입니다.
> DN 세포는 표면에 **CD4**도 없고 **CD8**도 없죠? 그럼 뭘로 구분하냐? 바로 **CD44**와 **CD25**입니다. 이 마커 변화를 외워야 합니다.
>
> > [!IMPORTANT] PAGE 10-11: DN1 ~ DN4 단계별 마커 (족보 테이블)
> > 11페이지 표를 보세요. **c-Kit (CD117)**, **CD44**, **CD25** 이 세 가지 마커의 변화 흐름을 잡아야 합니다.
> >
> > * **DN1 (Early):**
> >     * **마커:** `c-Kit++`, `CD44+`, `CD25-`
> >     * **특징:** 아직 흉선으로 이사 오는 중이거나 막 도착한 상태입니다. 아직 T세포로 완전히 결정되지 않아서(Multipotent), NK세포나 수지상세포(DC)로 빠질 수도 있는 시기입니다.
> >
> > * **DN2 (Commitment & Gene Rearrangement):**
> >     * **마커:** `c-Kit++`, `CD44+`, `CD25+` (**CD25가 양성으로 바뀜!**)
> >     * **핵심:** 여기서 **TCR 유전자 재배열($\gamma, \delta, \beta$)**이 시작됩니다. 그리고 7페이지에서 봤던 **Notch 신호**가 가장 강력하게 작용해서 "나는 이제 죽어도 T세포다"라고 **Commitment(계통 결정)**를 박는 시기입니다.
> >
> > * **DN3 ($\beta$-Selection Checkpoint):**
> >     * **마커:** `c-Kit+`, `CD44-`, `CD25+` (**CD44가 음성으로 바뀜!**)
> >     * **핵심:** 가장 중요합니다. 여기서 **$\beta$-selection**이 일어납니다. 즉, "TCR $\beta$ 사슬을 제대로 만들었니?" 검사하는 단계입니다. 통과 못 하면? 죽습니다(Apoptosis). Pre-TCR이 발현되는 시기이기도 하죠.
> >
> > * **DN4 (Pre-DP):**
> >     * **마커:** `c-Kit low/-`, `CD44-`, `CD25-` (**둘 다 음성!**)
> >     * **특징:** $\beta$-selection 통과했으니 기분 좋아서 미친듯이 **증식(Proliferation)**합니다. 그리고 이제 **$\alpha$ 사슬 재배열**을 준비하면서 **DP(Double Positive)** 단계로 넘어갑니다.
>
> > [!INFO] PAGE 13: TCR의 구조 ($\alpha\beta$ vs $\gamma\delta$)
> > 그림을 보세요. T세포는 두 종류의 수용체 중 하나를 가집니다.
> > * **$\alpha\beta$ TCR:** 우리 몸 T세포의 95% 이상. 적응면역의 주역이죠.
> > * **$\gamma\delta$ TCR:** 5% 미만. 주로 점막(Mucosa)이나 피부에 박혀서 선천면역처럼 작용합니다.
> > * 구조적으로 둘 다 **V(Variable)** 영역과 **C(Constant)** 영역이 있고, 세포막에 박혀 있죠? 옆에 **CD3 복합체($\epsilon, \delta, \gamma, \zeta$)**가 붙어있는 것도 똑같습니다. (CD3 없으면 신호 전달 못 합니다.)
>
> > [!TIP] 💡 PAGE 14: 확률 게임 (The Race Model)
> > 14페이지 텍스트를 씹어먹어 봅시다. 왜 $\alpha\beta$ T세포가 압도적으로 많을까요?
> > **"확률(Probability)"** 싸움입니다.
> > * **규칙:** DN2~DN3 단계에서 $\gamma, \delta, \beta$ 유전자 재배열이 동시에 시작됩니다(경주 시작!).
> > * **$\gamma\delta$ T세포가 되려면:** $\gamma$ 사슬과 $\delta$ 사슬 **두 개가 모두** 성공적으로 재배열되어야 합니다. (이벤트 2개 필요)
> > * **$\alpha\beta$ (정확히는 Pre-TCR) T세포가 되려면:** $\beta$ 사슬 **하나만** 성공하면 일단 멈추고($\beta$-selection), 증식한 뒤에 나중에 $\alpha$를 만듭니다. (이벤트 1개 필요)
> > * **결론:** 1개만 성공하면 되는 $\beta$ 쪽이 2개를 다 성공해야 하는 $\gamma\delta$보다 확률적으로 훨씬 유리합니다. 그래서 3배 이상 $\alpha\beta$ 쪽으로 많이 가는 겁니다.

> [!NOTE] Pages 15-20: $\gamma\delta$ T세포와 운명의 관문 ($\beta$-Selection)
> 자, 확률 게임에서 밀린 **$\gamma\delta$ T세포** 이야기 잠깐 하고, T세포 발달사에서 가장 중요한 **$\beta$-Selection**으로 넘어갑니다. 집중하세요.
>
> > [!INFO] PAGE 15: 태아 시기의 파동 (Waves)
> > 15페이지 그래프 보세요. X축이 **태아 발생일(Days of gestation)**입니다.
> > * **14~15일경:** 까만 선(**$\gamma\delta$ Thymocytes**)이 먼저 확 치솟습니다. 태아 때는 $\gamma\delta$가 먼저 만들어져요. 왜? 만들기 쉬우니까요. (단순하잖아)
> > * **출생(Birth) 이후:** 파란 선(**$\alpha\beta$ Thymocytes**)이 역전해서 압도적으로 많아집니다. 성인의 T세포 중 $\gamma\delta$는 **0.5%**밖에 안 됩니다.
>
> > [!INFO] PAGE 16: $\gamma\delta$ T세포의 마이웨이
> > 이놈들은 $\alpha\beta$와는 가는 길이 다릅니다. **"DP(Double Positive) 단계"를 안 거칩니다.**
> > * **특징 3가지 (외우세요):**
> >     1.  흉선을 나갈 때 **DN(CD4-CD8-)** 상태로 나갑니다. (쿨하게 나감)
> >     2.  **MHC 제한**이 없습니다. 이상한 항원(Lipid 등)을 인식해요.
> >     3.  주로 **점막(Mucosa)이나 피부(Skin)**로 가서 박혀 있습니다. 선천면역(Innate)처럼 최전방 방어선 역할을 하죠.
>
> > [!IMPORTANT] PAGE 18-19: $\beta$-Selection (생사가 걸린 검문소)
> > 18페이지 그림에 빨간 박스로 **$\beta$-selection** 표시돼 있죠? 별표 다섯 개 치세요. DN3 단계에서 일어나는 가장 결정적인 사건입니다.
> > * **상황:** $\beta$ 사슬 재배열을 끝냈습니다. 근데 이게 제대로 만들어졌는지 어떻게 알까요? 짝꿍인 $\alpha$ 사슬은 아직 안 만들었는데?
> > * **해결책 (Pre-TCR):** 그래서 **Pre-T$\alpha$**라는 가짜(Surrogate) $\alpha$ 사슬을 붙여봅니다. 이게 $\beta$ 사슬이랑 잘 붙어서 세포막에 뜨면 "합격" 신호가 터집니다.
> > * **신호의 결과 (4가지 기전 - 시험 나옵니다):**
> >     1.  **Stop $\beta$-rearrangement (Allelic Exclusion):** "하나 성공했으면 됐어. 다른 쪽 염색체 $\beta$ 유전자는 건드리지 마." (단일 특이성 보장)
> >     2.  **Proliferation (증식):** "성공한 놈이니까 복제해!" 세포 수가 폭발적으로 늘어납니다. (DN4 단계)
> >     3.  **Start $\alpha$-rearrangement:** "자, 이제 진짜 짝꿍($\alpha$) 만들자."
> >     4.  **Expression of CD4/CD8:** "이제 옷 입자." DP 단계로 넘어갑니다.
>
> > [!TIP] 💡 PAGE 20: RAG 발현의 파동 (기출)
> > 20페이지 아래쪽 그래프 보세요. **RAG(Recombination Activating Gene)** 효소 수치가 오르락내리락하죠?
> > * **1차 피크 (DN2~3):** $\beta$ 사슬 자르느라 RAG가 높습니다.
> > * **급격한 감소 (DN3~4):** $\beta$-selection 통과 후 **증식(Proliferation)**할 때는 RAG를 끕니다. (세포 분열 중에 DNA 자르면 큰일 나니까요. 이거 중요합니다!)
> > * **2차 피크 (DP):** 증식 끝나고 $\alpha$ 사슬 자르려니 다시 RAG가 올라갑니다. 이 흐름을 이해해야 그래프 문제 풉니다.

> [!NOTE] Pages 21-26: 양성 선택과 음성 선택의 서막 (지옥의 훈련소)
> 자, 유전자 재배열도 끝났고 $\beta$-selection도 통과해서 DP(Double Positive)가 됐습니다. 이제부터 진짜 '고시'가 시작됩니다.
> 23페이지 수치를 보세요. **98%가 죽습니다.** 단 2%만 살아남는 지옥의 훈련소, 그 원리를 파헤쳐 봅시다.
>
> > [!INFO] PAGE 22: 노벨상 수상자 (Doherty & Zinkernagel)
> > 이 아저씨들 얼굴 보고 지나가지 마세요. 이분들이 **MHC Restriction(MHC 제한)** 개념을 발견해서 노벨상 탔습니다.
> > * **핵심 개념 (외우세요):**
> >     * **Positive Selection (양성 선택):** 자기 MHC를 **'적당히(Low affinity)'** 인식할 줄 아는 놈만 살립니다. -> 결과: **MHC Restriction** 획득.
> >     * **Negative Selection (음성 선택):** 자기 MHC+자기 펩타이드에 **'너무 세게(High affinity)'** 반응하는 놈은 죽입니다. -> 결과: **Self-Tolerance(자기 관용)** 획득.
> > * 즉, **"너무 무관심해도 죽고(Neglect), 너무 집착해도 죽는다(Negative)."** 적당한 놈만 사는 겁니다. (Goldilocks hypothesis)
>
> > [!IMPORTANT] PAGE 25: MHC Restriction 증명 실험 (야마/기출)
> > **이 실험 100% 시험 나옵니다.** 별표 다섯 개 치세요. 방사선 조사 쥐(Chimera) 실험입니다.
> > 논리를 단계별로 따라오세요.
> > 1.  **준비물:**
> >     * **(A x B) F1 쥐:** 유전적으로 MHC A형과 B형을 둘 다 가짐.
> >     * **Strain B 쥐:** MHC B형만 가짐. (흉선을 제공할 대리모)
> > 2.  **실험 과정:**
> >     * Strain B 쥐에 방사선을 쏴서 자기 면역세포를 다 죽이고, **(A x B) F1의 골수(Stem cells)**를 이식합니다.
> >     * 그럼 F1 유전자를 가진 T세포가 **Strain B의 흉선(Thymus)**에서 교육받고 자라겠죠?
> > 3.  **결과 (핵심):**
> >     * 다 큰 T세포를 꺼내서 바이러스 감염된 세포를 죽이게 했더니, **Strain B 세포는 죽이는데(Killing), Strain A 세포는 못 죽입니다(No killing).**
> > 4.  **결론 (Interpretation):**
> >     * T세포의 **유전자**는 A, B 둘 다 가지고 있었지만, **흉선 학교가 B형**이라서 **"B형 MHC 보는 법"만 배웠다**는 겁니다.
> >     * 즉, **"MHC Restriction은 유전자가 아니라 흉선 환경(Thymus Environment)에 의해 학습된다."** 이게 정답입니다.
>
> > [!INFO] PAGE 26: 선택의 장소 (Cortex vs Medulla)
> > 그림의 위치와 비율을 보세요.
> > * **Cortex (피질):** 여기서 **Positive Selection**이 주로 일어납니다. 담당 교관은 **cTEC**입니다.
> > * **Death by Neglect (90~96%):** 그림 오른쪽 보세요. 대부분의 세포는 자기 MHC를 아예 인식 못 해서 여기서 그냥 **굶어 죽습니다(Apoptosis)**. 억울하게 죽는 게 아니라 무능해서 죽는 겁니다.
> > * **Medulla (수질):** 살아남은 애들이 여기로 와서 **Negative Selection**을 받습니다. 담당 교관은 **mTEC, DC(수지상세포)**입니다. 여기서 자기 몸 공격할 미친 놈들을 걸러냅니다.

> [!NOTE] Pages 27-33: MHC 제한과 H-Y 형질전환 마우스 실험 (실험 데이터 해석의 꽃)
> 자, 앞서 배운 MHC Restriction과 Negative Selection 이론을 실제로 증명한 전설적인 실험이 나옵니다.
> **H-Y Transgenic Mouse 실험**은 면역학 실험 데이터 해석 문제의 '조상님'입니다. FACS(유세포 분석) 데이터를 읽을 줄 모르면 시험장에 들어갈 생각도 하지 마세요.
>
> > [!INFO] PAGE 28-29: 친화력 모델 (Goldilocks Hypothesis)
> > 28페이지 그림을 봅시다. T세포의 운명은 **"TCR이 자기 MHC+자기 펩타이드를 얼마나 세게 잡느냐(Affinity)"**에 달려 있습니다.
> > * **No Interaction (무반응):** 90~96%가 해당됩니다. 아예 인식을 못 하니 쓸모가 없죠? **Death by Neglect (방치되어 사망)**.
> > * **High Affinity (너무 강함):** 자기 몸을 공격할 놈들입니다. 위험하죠? **Negative Selection (음성 선택)**으로 제거(Apoptosis)됩니다.
> > * **Low/Intermediate Affinity (적당함):** "어? 이거 내 MHC네?" 하고 살짝 건드리는 정도. 이놈들만 **Positive Selection (양성 선택)**으로 살아남아 **SP(Single Positive)**가 됩니다.
> > * **핵심:** 너무 차가워도 안 되고, 너무 뜨거워도 안 됩니다. 딱 적당해야 합니다.
>
> > [!IMPORTANT] PAGE 30: H-Y Transgenic Mouse 실험 셋업 (족보)
> > 30페이지 실험 설계를 뜯어봅시다. 조건이 복잡하니 집중하세요.
> > * **H-Y 항원:** 수컷(Male)에만 있는 항원입니다. (Y염색체 유래). 즉, **수컷에게는 'Self'**이고, **암컷에게는 'None'**입니다.
> > * **Transgenic TCR:** 연구자가 조작해서 넣어준 TCR입니다. 이 TCR은 **H-Y 항원**을 **H-2D^b (MHC Class I)**에 얹어서 제시할 때만 알아봅니다.
> > * **실험군 4가지:**
> >     1.  **Female H2-D^b:** H-Y 항원 없음 (적당한 결합 예상 -> 양성 선택).
> >     2.  **Male H2-D^b:** H-Y 항원 있음 (너무 강한 결합 예상 -> 음성 선택).
> >     3.  **Female H2-D^d:** MHC 종류가 다름 (결합 안 됨 -> 무시).
>
> > [!TIP] 💡 PAGE 31-33: FACS 데이터 해석 (기출 포인트)
> > 33페이지 FACS Plot을 보세요. X축은 **CD8**, Y축은 **CD4**입니다. 이 그림 해석하는 게 시험 문제입니다.
> >
> > * **1. Female H2-D^b (가운데 그림):**
> >     * **상황:** H-Y 항원이 없으므로 TCR이 '적당히' MHC만 인식합니다.
> >     * **결과:** **CD8+ SP 세포(오른쪽 아래, 37%)**가 뙇 하고 존재합니다.
> >     * **해석:** **Positive Selection**이 정상적으로 일어나서 CD8 T세포로 분화했습니다. (MHC Class I은 CD8을 만드니까요).
> >
> > * **2. Male H2-D^b (왼쪽 그림):**
> >     * **상황:** 수컷이라 H-Y 항원이 쫙 깔려 있습니다. TCR이 자기 항원(H-Y)을 '너무 세게' 뭅니다.
> >     * **결과:** CD8+ SP가 거의 없고(2%), **CD8low** 상태로 찌그러져 있거나 죽었습니다.
> >     * **해석:** **Negative Selection (Deletion)**이 일어나서 다 죽어나간 겁니다. 자기 반응성 세포를 없애는 과정이죠.
> >
> > * **3. Female H2-D^d (오른쪽 그림):**
> >     * **상황:** MHC 유전자가 **D^d**입니다. 이 TCR은 **D^b**만 좋아합니다. 짝이 안 맞죠?
> >     * **결과:** SP 세포가 아예 없습니다(0~3%). DP 단계(오른쪽 위)에만 머물러 있죠?
> >     * **해석:** 인식을 못 하니 양성 선택을 못 받아서 **Death by Neglect** 당한 겁니다. **"MHC Restriction"**을 증명하는 결과죠.
> >
> > * **결론:** 이 세 가지 그림을 보고 "양성 선택", "음성 선택", "MHC 제한"을 각각 매칭할 수 있어야 합니다.


> [!NOTE] Pages 34-37: 양성 선택의 분자적 기전 (THEMIS의 등장)
> 단순히 "적당히 결합하면 산다"로 끝내면 의대 수업이 아니죠. 그 신호가 세포 안에서 구체적으로 어떻게 전달되는지, **THEMIS**라는 단백질을 중심으로 파고듭니다.
>
> > [!INFO] PAGE 35: Death by Neglect (무시당한 자의 최후)
> > 35페이지 텍스트 보세요. 양성 선택(Positive Selection)을 통과하지 못한 세포들은 **3~4일** 안에 생존 신호를 못 받아서 **Apoptosis(세포자멸사)**로 죽습니다.
> > * 왜 이렇게 많이 죽일까요? (이유 2가지)
> >     1.  **Cluttering 방지:** 아무것도 인식 못 하는 멍청한 세포가 몸을 돌아다니며 공간만 차지하는 걸 막기 위함.
> >     2.  **확률 높이기:** 진짜 항원을 만날 확률이 있는 놈들만 남겨놔야 면역 효율이 올라가니까요.
>
> > [!TIP] 💡 PAGE 37: THEMIS Signaling Pathway (신상 족보)
> > 37페이지 그림, **THEMIS** 박스에 별표(야마) 쳐져 있죠? 이게 비교적 최근에 밝혀진 **가슴샘 세포 특이적 신호 분자**입니다.
> > * **위치:** 그림을 보면 **TCR 신호 전달 경로(Lck -> ZAP70 -> LAT)** 사이에 딱 끼어 있습니다.
> > * **작동 기전 (Mechanism):**
> >     * THEMIS는 **GRB-2**를 통해 **SHP-1 (Phosphatase, 인산분해효소)**을 끌고 옵니다.
> >     * **SHP-1**은 신호를 **끄는(Dampening)** 역할을 하죠.
> >     * **결과:** TCR 신호가 너무 강하지 않게 적절히 조절해서, 약한 신호(Low affinity)에서도 세포가 "어? 이거 양성 선택 신호네?"라고 알아먹고 생존하도록 돕습니다.
> > * **한마디로:** **"Positive Selection을 가능하게 하는 신호 튜너(Tuner)"**입니다. 이거 없으면 양성 선택이 안 됩니다.


> [!NOTE] Pages 38-46: 음성 선택과 AIRE (내 몸을 지키는 그림자)
> 이제 수질(Medulla)로 넘어왔습니다. 여기서 가장 중요한 건 **AIRE (AutoImmune Regulator)**입니다. 이건 면역학 전체를 통틀어 가장 중요한 개념 중 하나입니다.
>
> > [!IMPORTANT] PAGE 40: mTEC과 수지상세포의 협동
> > 40페이지 그림을 보세요. 음성 선택(Negative Selection)은 누가 시킵니까?
> > * **주연:** **mTEC (수질 가슴샘 상피세포)**.
> > * **조연:** **Dendritic Cell (수지상세포)**. mTEC이 만든 항원을 주워먹고 대신 제시해주기도 합니다.
> > * 이 과정이 실패하면? 자기 반응성 세포가 나가서 **자가면역질환(Autoimmune disease)**을 일으킵니다. 대표적인 예가 **제1형 당뇨병(T1D)**이죠.
>
> > [!TIP] 💡 PAGE 44-46: AIRE와 TSA (자가면역의 핵심 기전)
> > 44페이지 텍스트 보세요. 흉선(Thymus)은 심장도 아니고 췌장도 아닌데, 어떻게 심장이나 췌장 세포를 공격할 놈을 미리 걸러낼까요?
> > * **TSA (Tissue-Specific Antigens):** 인슐린(췌장), 티로글로불린(갑상선) 같은 특정 조직 항원들을 말합니다.
> > * **AIRE의 역할 (핵심):** **mTEC**에만 있는 **AIRE 단백질**이 이 TSA 유전자들을 흉선에서 강제로 발현시킵니다. 일종의 **"전신 항원 미리보기 서비스(Shadow)"**를 제공하는 거죠.
> > * **분자 기전 (46페이지 그림 상세):**
> >     * AIRE는 닫혀 있는(Silenced) 염색질에 접근해서 **RNA Polymerase**를 끌고 옵니다.
> >     * 그림에 **Ac(아세틸화), Me(메틸화)** 보이죠? 후성유전학적(Epigenetic) 조절을 통해 꽁꽁 숨겨진 유전자를 억지로 읽어내는 겁니다.
> > * **결론:** AIRE가 고장 나면? 흉선에서 인슐린을 못 보여줍니다. -> 인슐린 공격하는 T세포가 살아서 나갑니다. -> **당뇨병** 걸립니다. (APECED 증후군)


> [!NOTE] Pages 47-53: 흉선의 역설 (Paradox)과 해결책
> 여기서 아주 날카로운 질문이 나옵니다. "아니, 양성 선택할 때 자기 MHC랑 반응하는 놈을 살린다며? 근데 음성 선택 때는 자기 MHC랑 반응하는 놈을 죽인다며? 그럼 다 죽어야 하는 거 아냐?"
> 이 **Thymic Paradox**를 해결하는 기가 막힌 기전을 설명합니다.
>
> > [!INFO] PAGE 50: OT-I / TAP1 실험 (펩타이드가 다르다!)
> > 50페이지 실험을 보세요. 이 모순을 풀기 위한 실험입니다.
> > * **TAP1 KO 쥐:** 펩타이드 수송체가 고장 나서 MHC가 텅 비어 있습니다(Empty MHC). -> 세포 다 죽음 (Death by neglect).
> > * **Low affinity Peptide 추가:** 살짝만 붙는 펩타이드를 넣어줬더니 -> **생존 (Positive Selection)**.
> > * **High affinity Peptide 추가:** 꽉 붙는 펩타이드를 넣어줬더니 -> **사망 (Negative Selection)**.
> > * **결론:** 결국 **"펩타이드와의 결합 세기(Affinity)"**가 생사를 가릅니다.
>
> > [!IMPORTANT] PAGE 52-53: Thymoproteasome ($\beta$ 5t) - 비밀병기
> > 53페이지 그림이 그 해답의 결정타입니다. 피질 상피세포(cTEC)는 단백질을 자르는 가위가 다릅니다.
> > * **일반 세포:** 일반 프로테아좀을 씁니다.
> > * **cTEC (피질 세포):** **$\beta$5t**라는 특수 소단위체를 가진 **Thymoproteasome**을 씁니다.
> > * **기능:** 이 특수 가위는 단백질을 듬성듬성 잘라서 **'결합력이 약한(Low affinity)' 독특한 펩타이드**를 만듭니다.
> > * **해결:**
> >     1.  **Cortex:** cTEC이 만든 '약한 펩타이드'로 **양성 선택** (살살 달래서 살림).
> >     2.  **Medulla:** mTEC이나 DC가 만든 '진짜(강한) 펩타이드'로 **음성 선택** (세게 반응하는 놈 제거).
> >     * 이렇게 장소별로 **'메뉴(Peptide)'**를 다르게 해서 패러독스를 해결합니다.
> 
> >[!quote] 의문: PS에서 결합력이 약한 펩티드와 결합할 정도의 애면 NS에선 무조건 걸러지는거 아닌가?
> > - PS의 통과자는 **자기 MHC**를 인식할 수만 있으면 됨. 예컨대 자기 MHC+적당한 Peptide를 넣어버려서 **"약한 결합력"을 가지는 대신 MHC를 인식**할 수 있으면 통과.
> > - NS에서는 **결합력이 강한 Self peptide**를 제시해버려서, 조금이라도 자기 peptide와 결합할 수 있는 녀석은 모두 제거시키는거임.
> > - **결론: Peptide의 결합력 뿐만 아니라, 종류도 다르다**


> [!NOTE] Pages 54-60: 계통 결정 (Lineage Commitment) - CD4냐 CD8이냐
> DP 세포가 시험을 다 통과했습니다. 이제 옷을 갈아입어야죠. Helper(CD4)가 될지, Cytotoxic(CD8)이 될지 어떻게 정할까요?
>
> > [!IMPORTANT] PAGE 58: Kinetic Signaling Model (역동 신호 모델)
> > 58페이지 그림, **Singer 박사님** 이론입니다. 이게 최신 정설입니다. (야마!)
> > * **핵심:** "신호가 **끊기냐 지속되냐**가 운명을 가른다."
> > * **과정:**
> >     1.  양성 선택을 받으면 일단 **모든 DP 세포**는 **CD8 발현을 줄입니다(CD4+8lo)**.
> >     2.  **이때!**
> >         * **MHC II와 결합하던 놈:** CD4는 그대로 있으니 신호가 **계속(Continuous)** 들어옵니다 -> **CD4 T세포**가 됩니다.
> >         * **MHC I과 결합하던 놈:** CD8이 줄어드니까 신호가 **끊깁니다(Disrupted)**. 신호가 끊기면 **IL-7** 신호를 받아서 다시 CD8을 만들고 **CD8 T세포**가 됩니다.
> > * **요약:** 신호 지속(Continuous) = CD4, 신호 중단(Interrupted) + IL-7 구조 = CD8.
>
> > [!TIP] 💡 PAGE 59: Transcription Factor Switch (ThPOK vs Runx3)
> > 59페이지 그림의 분자 스위치를 외우세요. 서로 억제하는 관계입니다.
> > * **ThPOK:** **CD4**로 가는 열쇠. (T-Helper-POK).
> > * **Runx3:** **CD8**로 가는 열쇠.
> > * **기전:** ThPOK가 뜨면 Runx3를 누르고(CD4 됨), Runx3가 뜨면 ThPOK를 누릅니다(CD8 됨).


> [!NOTE] Pages 61-67: 졸업과 흉선 탈출 (Exit)
> 드디어 졸업입니다. 다 큰 T세포가 흉선을 떠나는 과정도 그냥 나가는 게 아닙니다.
>
> > [!INFO] PAGE 62: S1PR1과 탈출 기전
> > 62페이지 그림의 순서를 보세요.
> > 1.  **Foxo1 (전사인자)**이 활성화됩니다.
> > 2.  Foxo1이 **KLF2**를 켜고, KLF2가 **S1PR1 (스핑고신-1-인산 수용체)**을 발현시킵니다.
> > 3.  혈액 속에는 **S1P (Sphingosine-1-Phosphate)** 농도가 높습니다.
> > 4.  T세포의 S1PR1이 핏속의 S1P 냄새를 맡고 혈관으로 **Egress(탈출)**합니다.
> > * 참고: 흉선 안에서는 S1P 농도가 낮게 유지되어서 미성숙 세포가 못 나가게 막습니다.
>
> > [!INFO] PAGE 65-66: Treg (평화 유지군)
> > 마지막 보너스. 자기 반응성이 살짝 높은 애들(High affinity) 중 일부는 죽이지 않고 **Treg (조절 T세포)**로 스카우트합니다.
> > * **마커:** **FoxP3** (전사인자), **CD25**, **CD4**.
> > * **기능:** 사회(말초 조직)에 나가서 과도한 면역 반응을 억제합니다(Suppress). 사이토카인 뺏어먹기, 억제 물질 뿌리기 등으로 평화를 유지합니다.
], ['\\(', '\\)'\|',
    displayMath: [['$$', '$$'], ['\\[', '\\]']],
    processEscapes: true,
  },
  svg: {
    fontCache: 'global'
  }
};
</script>
<script type="text/javascript" id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-svg.js">
</script>

>[!quote] 공지
>본 자료의 저작권은 KAISTUDY에 있습니다.

---

> [!abstract]- 강의 요약: T세포의 발달 (T Cell Development)
>
> 이번 강의는 **Thymus**에 입학한 전구세포가 엄격한 **Selection**을 거쳐 정예 T세포로 졸업하는 과정을 다룹니다. 크게 **초기 발달(DN) -> 선택(DP) -> 계통 결정(SP) -> 졸업**의 흐름입니다.
>
> 1.  **Early Development (입학 및 진로 결정)**
>     * **장소:** Bone Marrow에서 온 전구세포가 **흉선(Thymus)**의 피질(Cortex)로 진입.
>     * **Notch 신호:** T세포가 되기 위한 필수 신호. (Notch1 없으면 B세포 됨).
>     * **DN 단계 (CD4-CD8-):** **CD44**와 **CD25** 마커 변화(DN1→DN2→DN3→DN4)를 통해 구분하며, **DN3** 단계에서 **$\beta$-Selection**을 통해 첫 번째 관문을 통과함.
>
> 2.  **$\beta$-Selection & Proliferation (중간 점검)**
>     * **Pre-TCR:** 기능적인 $\beta$ 사슬이 만들어졌는지 **Pre-T$\alpha$**와 결합해 확인.
>     * **결과:** 통과 시 **Allelic Exclusion**($\beta$ 유전자 재배열 중단), **대량 증식**, CD4/CD8 발현(DP 진입).
>
> 3.  **Selection Processes (졸업 시험: 98% 탈락)**
>     * **Positive Selection (Cortex):** **cTEC**이 제시하는 MHC를 **'적당히(Low affinity)'** 인식하면 생존. -> **MHC Restriction** 획득. (실패 시 Death by Neglect).
>     * **Negative Selection (Medulla):** **mTEC/DC**가 제시하는 자기 항원(Self-Ag)을 **'너무 세게(High affinity)'** 인식하면 제거. -> **Self-Tolerance** 획득.
>     * **Paradox 해결:** **Thymoproteasome($beta$ 5t)**이 피질에서 독특한 펩타이드를 만들어 양성 선택을 도움.
>
> 4.  **Lineage Commitment & Exit (진로 선택 및 졸업)**
>     * **CD4 vs CD8:** **Kinetic Signaling Model**에 따라 신호가 지속되면(Continuous) **CD4**, 끊기면(Interrupted) **CD8**이 됨. (전사인자 **ThPOK** vs **Runx3**의 길항 작용).
>     * **Exit:** **S1P-S1PR1** 상호작용을 통해 성숙한 T세포가 혈관으로 탈출.

> [!example]- 핵심 키워드 정리 (Key Terms & Concepts)
>
> ### 1. DN Stages & Checkpoints (족보)
> * **Notch1:** T세포 운명 결정의 핵심 (Notch on = T cell, Notch off = B cell).
> * **DN Markers:**
>     * **DN1:** `c-Kit++`, `CD44+`, `CD25-`
>     * **DN2:** `c-Kit++`, `CD44+`, **`CD25+`** (TCR 재배열 시작, Commitment).
>     * **DN3:** `c-Kit+`, **`CD44-`**, `CD25+` (**$\beta$-Selection**, Pre-TCR).
>     * **DN4:** `c-Kit-`, `CD44-`, **`CD25-`** (Proliferation, DP 준비).
> * **$\beta$-Selection:** DN3 단계. Pre-TCR 형성 확인 -> **Allelic Exclusion** 유도 -> **RAG 일시 중단** 및 증식.
>
> ### 2. Positive & Negative Selection (핵심 기전)
> * **Goldilocks Hypothesis:** 결합력이 너무 약해도(Neglect), 너무 강해도(Negative) 죽고, **적당해야(Positive)** 산다.
> * **MHC Restriction:** 흉선 환경(Thymus Stroma)에 의해 학습됨. (Chimera 실험: F1 골수 -> Parent B 흉선 이식 시 B형 MHC만 인식).
> * **H-Y Transgenic Mouse:**
>     * 수컷(Male): H-Y 항원 있음 -> 고친화력 -> **Negative Selection (Deletion)**.
>     * 암컷(Female): H-Y 항원 없음 -> 적당한 친화력 -> **Positive Selection (CD8 SP 생존)**.
> * **THEMIS:** 양성 선택 시 TCR 신호 감도 조절(Dampening by SHP-1).
> * **AIRE (AutoImmune Regulator):** 수질(mTEC)에서 췌장, 갑상선 등 **TSA(조직 특이 항원)**를 강제 발현시켜 자가반응성 T세포 제거. (결핍 시 자가면역질환).
> * **Thymoproteasome ($\beta$5t):** cTEC 특이적. 저친화력 펩타이드 생성 -> 양성 선택 유도.
>
> ### 3. Lineage Commitment (CD4 vs CD8)
> * **Kinetic Signaling Model (Singer):**
>     * MHC II 결합 -> CD8 down -> 신호 **지속(Continuous)** -> **CD4** 분화 (**ThPOK**).
>     * MHC I 결합 -> CD8 down -> 신호 **중단(Disrupted)** -> IL-7 신호 -> **CD8** 재발현 및 분화 (**Runx3**).
>
> ### 4. Graduation (Exit)
> * **S1PR1 & S1P:** 흉선 성숙 완료 시 **Foxo1 -> KLF2 -> S1PR1** 발현. 혈액 내 높은 S1P 농도를 따라 흉선 탈출(Egress).

---

> [!NOTE] Pages 1-5: T세포 발달의 개요와 흉선의 해부학적 구조
> 자, 먼저 숲을 보고 나무를 봅시다. T세포가 어디서 태어나서 어디로 가는지, 그 '학교'의 구조가 어떻게 생겨먹었는지부터 잡고 갑니다.
>
> > [!INFO] PAGE 2: 흉선의 퇴화 (Involution)
> > 2페이지 상단의 그림을 보세요. 아기 때(기어갈 때)는 흉선이 빵빵하죠? 그런데 나이 들수록(지팡이 짚을 때) 어떻게 됩니까? 쪼그라듭니다.
> > * **지방화(Fatty degeneration):** 나이가 들면 흉선 실질이 지방으로 대체되면서 T세포 생산 능력이 떨어집니다. 이게 노인 면역 저하의 원인 중 하나예요.
> > * **발달 타임라인:** 그림 아래쪽을 보면, **Bone Marrow(골수)**에서 온 전구세포가 **DN(Double Negative)** → **DP(Double Positive)** → **SP(Single Positive)** 단계로 성숙해가는 과정이 보이죠? 이 용어들, 오늘 지겹게 들을 거니 지금 눈에 익히세요.
>
> > [!INFO] PAGE 4: 흉선의 구조와 이동 경로 (Traffic)
> > 4페이지 그림 (a), (b), (c)를 같이 봅니다. T세포는 가만히 앉아서 크는 게 아니라, 흉선 안을 '이동'하면서 교육받습니다.
> > * **구조 (바깥 -> 안쪽):**
> >     1.  **Capsule (피막):** 껍데기.
> >     2.  **Subcapsular Cortex (피막하 피질):** 전구세포가 처음 들어와서 증식하는 곳.
> >     3.  **Cortex (피질/겉질):** 그림 (a)에서 진하게 염색된 부분. 여기서 **DN3, DN4, DP** 단계가 진행됩니다. **Positive Selection(양성선택)**의 주무대죠.
> >     4.  **Corticomedullary Junction:** 피질과 수질의 경계. 혈관(Blood vessel)이 여기로 들어옵니다. 전구세포도 여기로 들어오고, 다 큰 놈도 여기로 나갑니다.
> >     5.  **Medulla (수질/속질):** 그림 (a)에서 밝은 부분. **SP** 단계, **Negative Selection(음성선택)**이 일어납니다.
> > * **이동 경로 (화살표 보세요):** 혈관 타고 **CM Junction**으로 진입 -> **Subcapsular Cortex**로 이동 -> 다시 안쪽 **Cortex**로 진입 -> **Medulla** -> **Exit**. 이 동선을 기억해야 단계별 위치 문제를 맞춥니다.
>
> > [!INFO] PAGE 5: 흉선 상피세포 (Stroma)
> > T세포 혼자 크는 게 아닙니다. '선생님' 역할을 하는 상피세포들이 있어요.
> > * **cTECs (Cortical Thymic Epithelial Cells):** 피질에 있는 선생님. **Positive Selection** 담당.
> > * **mTECs (Medullary Thymic Epithelial Cells):** 수질에 있는 선생님. **Negative Selection** 담당.
> > * 이 세포들이 뭘 발현하느냐에 따라 T세포의 운명이 갈립니다.

> [!NOTE] Pages 6-9: 초기 발달과 Notch 신호 (운명의 갈림길)
> 흉선에 들어왔다고 무조건 T세포가 되는 게 아닙니다. "너 T세포 할래, B세포 할래?"를 결정하는 결정적인 신호가 있습니다. 여기서 **'야마(족보)'** 나옵니다.
>
> > [!IMPORTANT] PAGE 7: Notch Signaling (족보 포인트)
> > 7페이지 그림에 **"NOTCH"**라고 대문짝만하게 박혀 있고 **별표(야마)** 쳐져 있죠? 이거 무조건 나옵니다.
> > * **핵심:** 조혈모세포(HSC)가 흉선에 왔을 때, **Notch 신호**를 받아야만 T세포가 됩니다.
> > * **실험 증거 (텍스트 보세요):**
> >     1.  **Notch1 과발현(Overexpression):** 골수(Bone Marrow)에서도 T세포가 생겨버림 (원래는 B세포가 생겨야 함).
> >     2.  **Notch1 제거(Knockout):** 흉선(Thymus)인데도 T세포 대신 B세포가 생겨버림.
> > * **결론:** **"Notch = T cell lineage commitment"**. Notch가 있으면 T세포, 없으면 B세포입니다. (그림에서 B세포 쪽으로 가는 화살표에는 Notch 신호가 없는 걸 확인하세요!)
>
> > [!TIP] 💡 PAGE 8: OP9-DL1 실험 데이터 해석 (기출)
> > 이 데이터 해석하는 문제 자주 나옵니다. 8페이지 그림 뜯어봅시다.
> > * **실험 셋업:**
> >     * **OP9 세포:** 기질세포(Stromal cell).
> >     * **DL1 (Delta-like 1):** **Notch의 Ligand(리간드)**입니다. 즉, DL1이 있어야 Notch 신호를 줄 수 있습니다.
> > * **결과 그래프 (FACS Plot):**
> >     * **왼쪽 (Notch1 -/-):** Notch 수용체를 없앤 쥐. 흉선에 넣었는데도 **B세포(CD19+)**만 잔뜩 생깁니다. T세포는 안 생겨요.
> >     * **오른쪽 (Control):** 정상. T세포(Thy1+)가 잘 생깁니다.
> >     * **아래쪽 (OP9-DL1 배양):** 배양 접시에 **DL1(Notch 리간드)**을 깔아줬더니 줄기세포가 **DN1 -> DN2 -> DN3**로 쑥쑥 큽니다. (그림의 숫자 44, 25는 CD44, CD25 마커를 뜻함. 뒤에서 자세히 다룸).
> > * **한마디로:** 흉선 환경(Notch Ligand)이 없으면 T세포는 절대 못 만든다!

> [!NOTE] Pages 10-14: DN 단계의 세분화와 TCR 운명 결정 (Race)
> 자, 이제 **DN(Double Negative)** 단계를 현미경으로 들여다볼 시간입니다.
> 10페이지 그림과 11페이지 표, **이거 시험에 나옵니다.** 멍하니 "DN이구나" 하고 넘어가는 순간 유급입니다.
> DN 세포는 표면에 **CD4**도 없고 **CD8**도 없죠? 그럼 뭘로 구분하냐? 바로 **CD44**와 **CD25**입니다. 이 마커 변화를 외워야 합니다.
>
> > [!IMPORTANT] PAGE 10-11: DN1 ~ DN4 단계별 마커 (족보 테이블)
> > 11페이지 표를 보세요. **c-Kit (CD117)**, **CD44**, **CD25** 이 세 가지 마커의 변화 흐름을 잡아야 합니다.
> >
> > * **DN1 (Early):**
> >     * **마커:** `c-Kit++`, `CD44+`, `CD25-`
> >     * **특징:** 아직 흉선으로 이사 오는 중이거나 막 도착한 상태입니다. 아직 T세포로 완전히 결정되지 않아서(Multipotent), NK세포나 수지상세포(DC)로 빠질 수도 있는 시기입니다.
> >
> > * **DN2 (Commitment & Gene Rearrangement):**
> >     * **마커:** `c-Kit++`, `CD44+`, `CD25+` (**CD25가 양성으로 바뀜!**)
> >     * **핵심:** 여기서 **TCR 유전자 재배열($\gamma, \delta, \beta$)**이 시작됩니다. 그리고 7페이지에서 봤던 **Notch 신호**가 가장 강력하게 작용해서 "나는 이제 죽어도 T세포다"라고 **Commitment(계통 결정)**를 박는 시기입니다.
> >
> > * **DN3 ($\beta$-Selection Checkpoint):**
> >     * **마커:** `c-Kit+`, `CD44-`, `CD25+` (**CD44가 음성으로 바뀜!**)
> >     * **핵심:** 가장 중요합니다. 여기서 **$\beta$-selection**이 일어납니다. 즉, "TCR $\beta$ 사슬을 제대로 만들었니?" 검사하는 단계입니다. 통과 못 하면? 죽습니다(Apoptosis). Pre-TCR이 발현되는 시기이기도 하죠.
> >
> > * **DN4 (Pre-DP):**
> >     * **마커:** `c-Kit low/-`, `CD44-`, `CD25-` (**둘 다 음성!**)
> >     * **특징:** $\beta$-selection 통과했으니 기분 좋아서 미친듯이 **증식(Proliferation)**합니다. 그리고 이제 **$\alpha$ 사슬 재배열**을 준비하면서 **DP(Double Positive)** 단계로 넘어갑니다.
>
> > [!INFO] PAGE 13: TCR의 구조 ($\alpha\beta$ vs $\gamma\delta$)
> > 그림을 보세요. T세포는 두 종류의 수용체 중 하나를 가집니다.
> > * **$\alpha\beta$ TCR:** 우리 몸 T세포의 95% 이상. 적응면역의 주역이죠.
> > * **$\gamma\delta$ TCR:** 5% 미만. 주로 점막(Mucosa)이나 피부에 박혀서 선천면역처럼 작용합니다.
> > * 구조적으로 둘 다 **V(Variable)** 영역과 **C(Constant)** 영역이 있고, 세포막에 박혀 있죠? 옆에 **CD3 복합체($\epsilon, \delta, \gamma, \zeta$)**가 붙어있는 것도 똑같습니다. (CD3 없으면 신호 전달 못 합니다.)
>
> > [!TIP] 💡 PAGE 14: 확률 게임 (The Race Model)
> > 14페이지 텍스트를 씹어먹어 봅시다. 왜 $\alpha\beta$ T세포가 압도적으로 많을까요?
> > **"확률(Probability)"** 싸움입니다.
> > * **규칙:** DN2~DN3 단계에서 $\gamma, \delta, \beta$ 유전자 재배열이 동시에 시작됩니다(경주 시작!).
> > * **$\gamma\delta$ T세포가 되려면:** $\gamma$ 사슬과 $\delta$ 사슬 **두 개가 모두** 성공적으로 재배열되어야 합니다. (이벤트 2개 필요)
> > * **$\alpha\beta$ (정확히는 Pre-TCR) T세포가 되려면:** $\beta$ 사슬 **하나만** 성공하면 일단 멈추고($\beta$-selection), 증식한 뒤에 나중에 $\alpha$를 만듭니다. (이벤트 1개 필요)
> > * **결론:** 1개만 성공하면 되는 $\beta$ 쪽이 2개를 다 성공해야 하는 $\gamma\delta$보다 확률적으로 훨씬 유리합니다. 그래서 3배 이상 $\alpha\beta$ 쪽으로 많이 가는 겁니다.

> [!NOTE] Pages 15-20: $\gamma\delta$ T세포와 운명의 관문 ($\beta$-Selection)
> 자, 확률 게임에서 밀린 **$\gamma\delta$ T세포** 이야기 잠깐 하고, T세포 발달사에서 가장 중요한 **$\beta$-Selection**으로 넘어갑니다. 집중하세요.
>
> > [!INFO] PAGE 15: 태아 시기의 파동 (Waves)
> > 15페이지 그래프 보세요. X축이 **태아 발생일(Days of gestation)**입니다.
> > * **14~15일경:** 까만 선(**$\gamma\delta$ Thymocytes**)이 먼저 확 치솟습니다. 태아 때는 $\gamma\delta$가 먼저 만들어져요. 왜? 만들기 쉬우니까요. (단순하잖아)
> > * **출생(Birth) 이후:** 파란 선(**$\alpha\beta$ Thymocytes**)이 역전해서 압도적으로 많아집니다. 성인의 T세포 중 $\gamma\delta$는 **0.5%**밖에 안 됩니다.
>
> > [!INFO] PAGE 16: $\gamma\delta$ T세포의 마이웨이
> > 이놈들은 $\alpha\beta$와는 가는 길이 다릅니다. **"DP(Double Positive) 단계"를 안 거칩니다.**
> > * **특징 3가지 (외우세요):**
> >     1.  흉선을 나갈 때 **DN(CD4-CD8-)** 상태로 나갑니다. (쿨하게 나감)
> >     2.  **MHC 제한**이 없습니다. 이상한 항원(Lipid 등)을 인식해요.
> >     3.  주로 **점막(Mucosa)이나 피부(Skin)**로 가서 박혀 있습니다. 선천면역(Innate)처럼 최전방 방어선 역할을 하죠.
>
> > [!IMPORTANT] PAGE 18-19: $\beta$-Selection (생사가 걸린 검문소)
> > 18페이지 그림에 빨간 박스로 **$\beta$-selection** 표시돼 있죠? 별표 다섯 개 치세요. DN3 단계에서 일어나는 가장 결정적인 사건입니다.
> > * **상황:** $\beta$ 사슬 재배열을 끝냈습니다. 근데 이게 제대로 만들어졌는지 어떻게 알까요? 짝꿍인 $\alpha$ 사슬은 아직 안 만들었는데?
> > * **해결책 (Pre-TCR):** 그래서 **Pre-T$\alpha$**라는 가짜(Surrogate) $\alpha$ 사슬을 붙여봅니다. 이게 $\beta$ 사슬이랑 잘 붙어서 세포막에 뜨면 "합격" 신호가 터집니다.
> > * **신호의 결과 (4가지 기전 - 시험 나옵니다):**
> >     1.  **Stop $\beta$-rearrangement (Allelic Exclusion):** "하나 성공했으면 됐어. 다른 쪽 염색체 $\beta$ 유전자는 건드리지 마." (단일 특이성 보장)
> >     2.  **Proliferation (증식):** "성공한 놈이니까 복제해!" 세포 수가 폭발적으로 늘어납니다. (DN4 단계)
> >     3.  **Start $\alpha$-rearrangement:** "자, 이제 진짜 짝꿍($\alpha$) 만들자."
> >     4.  **Expression of CD4/CD8:** "이제 옷 입자." DP 단계로 넘어갑니다.
>
> > [!TIP] 💡 PAGE 20: RAG 발현의 파동 (기출)
> > 20페이지 아래쪽 그래프 보세요. **RAG(Recombination Activating Gene)** 효소 수치가 오르락내리락하죠?
> > * **1차 피크 (DN2~3):** $\beta$ 사슬 자르느라 RAG가 높습니다.
> > * **급격한 감소 (DN3~4):** $\beta$-selection 통과 후 **증식(Proliferation)**할 때는 RAG를 끕니다. (세포 분열 중에 DNA 자르면 큰일 나니까요. 이거 중요합니다!)
> > * **2차 피크 (DP):** 증식 끝나고 $\alpha$ 사슬 자르려니 다시 RAG가 올라갑니다. 이 흐름을 이해해야 그래프 문제 풉니다.

> [!NOTE] Pages 21-26: 양성 선택과 음성 선택의 서막 (지옥의 훈련소)
> 자, 유전자 재배열도 끝났고 $\beta$-selection도 통과해서 DP(Double Positive)가 됐습니다. 이제부터 진짜 '고시'가 시작됩니다.
> 23페이지 수치를 보세요. **98%가 죽습니다.** 단 2%만 살아남는 지옥의 훈련소, 그 원리를 파헤쳐 봅시다.
>
> > [!INFO] PAGE 22: 노벨상 수상자 (Doherty & Zinkernagel)
> > 이 아저씨들 얼굴 보고 지나가지 마세요. 이분들이 **MHC Restriction(MHC 제한)** 개념을 발견해서 노벨상 탔습니다.
> > * **핵심 개념 (외우세요):**
> >     * **Positive Selection (양성 선택):** 자기 MHC를 **'적당히(Low affinity)'** 인식할 줄 아는 놈만 살립니다. -> 결과: **MHC Restriction** 획득.
> >     * **Negative Selection (음성 선택):** 자기 MHC+자기 펩타이드에 **'너무 세게(High affinity)'** 반응하는 놈은 죽입니다. -> 결과: **Self-Tolerance(자기 관용)** 획득.
> > * 즉, **"너무 무관심해도 죽고(Neglect), 너무 집착해도 죽는다(Negative)."** 적당한 놈만 사는 겁니다. (Goldilocks hypothesis)
>
> > [!IMPORTANT] PAGE 25: MHC Restriction 증명 실험 (야마/기출)
> > **이 실험 100% 시험 나옵니다.** 별표 다섯 개 치세요. 방사선 조사 쥐(Chimera) 실험입니다.
> > 논리를 단계별로 따라오세요.
> > 1.  **준비물:**
> >     * **(A x B) F1 쥐:** 유전적으로 MHC A형과 B형을 둘 다 가짐.
> >     * **Strain B 쥐:** MHC B형만 가짐. (흉선을 제공할 대리모)
> > 2.  **실험 과정:**
> >     * Strain B 쥐에 방사선을 쏴서 자기 면역세포를 다 죽이고, **(A x B) F1의 골수(Stem cells)**를 이식합니다.
> >     * 그럼 F1 유전자를 가진 T세포가 **Strain B의 흉선(Thymus)**에서 교육받고 자라겠죠?
> > 3.  **결과 (핵심):**
> >     * 다 큰 T세포를 꺼내서 바이러스 감염된 세포를 죽이게 했더니, **Strain B 세포는 죽이는데(Killing), Strain A 세포는 못 죽입니다(No killing).**
> > 4.  **결론 (Interpretation):**
> >     * T세포의 **유전자**는 A, B 둘 다 가지고 있었지만, **흉선 학교가 B형**이라서 **"B형 MHC 보는 법"만 배웠다**는 겁니다.
> >     * 즉, **"MHC Restriction은 유전자가 아니라 흉선 환경(Thymus Environment)에 의해 학습된다."** 이게 정답입니다.
>
> > [!INFO] PAGE 26: 선택의 장소 (Cortex vs Medulla)
> > 그림의 위치와 비율을 보세요.
> > * **Cortex (피질):** 여기서 **Positive Selection**이 주로 일어납니다. 담당 교관은 **cTEC**입니다.
> > * **Death by Neglect (90~96%):** 그림 오른쪽 보세요. 대부분의 세포는 자기 MHC를 아예 인식 못 해서 여기서 그냥 **굶어 죽습니다(Apoptosis)**. 억울하게 죽는 게 아니라 무능해서 죽는 겁니다.
> > * **Medulla (수질):** 살아남은 애들이 여기로 와서 **Negative Selection**을 받습니다. 담당 교관은 **mTEC, DC(수지상세포)**입니다. 여기서 자기 몸 공격할 미친 놈들을 걸러냅니다.

> [!NOTE] Pages 27-33: MHC 제한과 H-Y 형질전환 마우스 실험 (실험 데이터 해석의 꽃)
> 자, 앞서 배운 MHC Restriction과 Negative Selection 이론을 실제로 증명한 전설적인 실험이 나옵니다.
> **H-Y Transgenic Mouse 실험**은 면역학 실험 데이터 해석 문제의 '조상님'입니다. FACS(유세포 분석) 데이터를 읽을 줄 모르면 시험장에 들어갈 생각도 하지 마세요.
>
> > [!INFO] PAGE 28-29: 친화력 모델 (Goldilocks Hypothesis)
> > 28페이지 그림을 봅시다. T세포의 운명은 **"TCR이 자기 MHC+자기 펩타이드를 얼마나 세게 잡느냐(Affinity)"**에 달려 있습니다.
> > * **No Interaction (무반응):** 90~96%가 해당됩니다. 아예 인식을 못 하니 쓸모가 없죠? **Death by Neglect (방치되어 사망)**.
> > * **High Affinity (너무 강함):** 자기 몸을 공격할 놈들입니다. 위험하죠? **Negative Selection (음성 선택)**으로 제거(Apoptosis)됩니다.
> > * **Low/Intermediate Affinity (적당함):** "어? 이거 내 MHC네?" 하고 살짝 건드리는 정도. 이놈들만 **Positive Selection (양성 선택)**으로 살아남아 **SP(Single Positive)**가 됩니다.
> > * **핵심:** 너무 차가워도 안 되고, 너무 뜨거워도 안 됩니다. 딱 적당해야 합니다.
>
> > [!IMPORTANT] PAGE 30: H-Y Transgenic Mouse 실험 셋업 (족보)
> > 30페이지 실험 설계를 뜯어봅시다. 조건이 복잡하니 집중하세요.
> > * **H-Y 항원:** 수컷(Male)에만 있는 항원입니다. (Y염색체 유래). 즉, **수컷에게는 'Self'**이고, **암컷에게는 'None'**입니다.
> > * **Transgenic TCR:** 연구자가 조작해서 넣어준 TCR입니다. 이 TCR은 **H-Y 항원**을 **H-2D^b (MHC Class I)**에 얹어서 제시할 때만 알아봅니다.
> > * **실험군 4가지:**
> >     1.  **Female H2-D^b:** H-Y 항원 없음 (적당한 결합 예상 -> 양성 선택).
> >     2.  **Male H2-D^b:** H-Y 항원 있음 (너무 강한 결합 예상 -> 음성 선택).
> >     3.  **Female H2-D^d:** MHC 종류가 다름 (결합 안 됨 -> 무시).
>
> > [!TIP] 💡 PAGE 31-33: FACS 데이터 해석 (기출 포인트)
> > 33페이지 FACS Plot을 보세요. X축은 **CD8**, Y축은 **CD4**입니다. 이 그림 해석하는 게 시험 문제입니다.
> >
> > * **1. Female H2-D^b (가운데 그림):**
> >     * **상황:** H-Y 항원이 없으므로 TCR이 '적당히' MHC만 인식합니다.
> >     * **결과:** **CD8+ SP 세포(오른쪽 아래, 37%)**가 뙇 하고 존재합니다.
> >     * **해석:** **Positive Selection**이 정상적으로 일어나서 CD8 T세포로 분화했습니다. (MHC Class I은 CD8을 만드니까요).
> >
> > * **2. Male H2-D^b (왼쪽 그림):**
> >     * **상황:** 수컷이라 H-Y 항원이 쫙 깔려 있습니다. TCR이 자기 항원(H-Y)을 '너무 세게' 뭅니다.
> >     * **결과:** CD8+ SP가 거의 없고(2%), **CD8low** 상태로 찌그러져 있거나 죽었습니다.
> >     * **해석:** **Negative Selection (Deletion)**이 일어나서 다 죽어나간 겁니다. 자기 반응성 세포를 없애는 과정이죠.
> >
> > * **3. Female H2-D^d (오른쪽 그림):**
> >     * **상황:** MHC 유전자가 **D^d**입니다. 이 TCR은 **D^b**만 좋아합니다. 짝이 안 맞죠?
> >     * **결과:** SP 세포가 아예 없습니다(0~3%). DP 단계(오른쪽 위)에만 머물러 있죠?
> >     * **해석:** 인식을 못 하니 양성 선택을 못 받아서 **Death by Neglect** 당한 겁니다. **"MHC Restriction"**을 증명하는 결과죠.
> >
> > * **결론:** 이 세 가지 그림을 보고 "양성 선택", "음성 선택", "MHC 제한"을 각각 매칭할 수 있어야 합니다.


> [!NOTE] Pages 34-37: 양성 선택의 분자적 기전 (THEMIS의 등장)
> 단순히 "적당히 결합하면 산다"로 끝내면 의대 수업이 아니죠. 그 신호가 세포 안에서 구체적으로 어떻게 전달되는지, **THEMIS**라는 단백질을 중심으로 파고듭니다.
>
> > [!INFO] PAGE 35: Death by Neglect (무시당한 자의 최후)
> > 35페이지 텍스트 보세요. 양성 선택(Positive Selection)을 통과하지 못한 세포들은 **3~4일** 안에 생존 신호를 못 받아서 **Apoptosis(세포자멸사)**로 죽습니다.
> > * 왜 이렇게 많이 죽일까요? (이유 2가지)
> >     1.  **Cluttering 방지:** 아무것도 인식 못 하는 멍청한 세포가 몸을 돌아다니며 공간만 차지하는 걸 막기 위함.
> >     2.  **확률 높이기:** 진짜 항원을 만날 확률이 있는 놈들만 남겨놔야 면역 효율이 올라가니까요.
>
> > [!TIP] 💡 PAGE 37: THEMIS Signaling Pathway (신상 족보)
> > 37페이지 그림, **THEMIS** 박스에 별표(야마) 쳐져 있죠? 이게 비교적 최근에 밝혀진 **가슴샘 세포 특이적 신호 분자**입니다.
> > * **위치:** 그림을 보면 **TCR 신호 전달 경로(Lck -> ZAP70 -> LAT)** 사이에 딱 끼어 있습니다.
> > * **작동 기전 (Mechanism):**
> >     * THEMIS는 **GRB-2**를 통해 **SHP-1 (Phosphatase, 인산분해효소)**을 끌고 옵니다.
> >     * **SHP-1**은 신호를 **끄는(Dampening)** 역할을 하죠.
> >     * **결과:** TCR 신호가 너무 강하지 않게 적절히 조절해서, 약한 신호(Low affinity)에서도 세포가 "어? 이거 양성 선택 신호네?"라고 알아먹고 생존하도록 돕습니다.
> > * **한마디로:** **"Positive Selection을 가능하게 하는 신호 튜너(Tuner)"**입니다. 이거 없으면 양성 선택이 안 됩니다.


> [!NOTE] Pages 38-46: 음성 선택과 AIRE (내 몸을 지키는 그림자)
> 이제 수질(Medulla)로 넘어왔습니다. 여기서 가장 중요한 건 **AIRE (AutoImmune Regulator)**입니다. 이건 면역학 전체를 통틀어 가장 중요한 개념 중 하나입니다.
>
> > [!IMPORTANT] PAGE 40: mTEC과 수지상세포의 협동
> > 40페이지 그림을 보세요. 음성 선택(Negative Selection)은 누가 시킵니까?
> > * **주연:** **mTEC (수질 가슴샘 상피세포)**.
> > * **조연:** **Dendritic Cell (수지상세포)**. mTEC이 만든 항원을 주워먹고 대신 제시해주기도 합니다.
> > * 이 과정이 실패하면? 자기 반응성 세포가 나가서 **자가면역질환(Autoimmune disease)**을 일으킵니다. 대표적인 예가 **제1형 당뇨병(T1D)**이죠.
>
> > [!TIP] 💡 PAGE 44-46: AIRE와 TSA (자가면역의 핵심 기전)
> > 44페이지 텍스트 보세요. 흉선(Thymus)은 심장도 아니고 췌장도 아닌데, 어떻게 심장이나 췌장 세포를 공격할 놈을 미리 걸러낼까요?
> > * **TSA (Tissue-Specific Antigens):** 인슐린(췌장), 티로글로불린(갑상선) 같은 특정 조직 항원들을 말합니다.
> > * **AIRE의 역할 (핵심):** **mTEC**에만 있는 **AIRE 단백질**이 이 TSA 유전자들을 흉선에서 강제로 발현시킵니다. 일종의 **"전신 항원 미리보기 서비스(Shadow)"**를 제공하는 거죠.
> > * **분자 기전 (46페이지 그림 상세):**
> >     * AIRE는 닫혀 있는(Silenced) 염색질에 접근해서 **RNA Polymerase**를 끌고 옵니다.
> >     * 그림에 **Ac(아세틸화), Me(메틸화)** 보이죠? 후성유전학적(Epigenetic) 조절을 통해 꽁꽁 숨겨진 유전자를 억지로 읽어내는 겁니다.
> > * **결론:** AIRE가 고장 나면? 흉선에서 인슐린을 못 보여줍니다. -> 인슐린 공격하는 T세포가 살아서 나갑니다. -> **당뇨병** 걸립니다. (APECED 증후군)


> [!NOTE] Pages 47-53: 흉선의 역설 (Paradox)과 해결책
> 여기서 아주 날카로운 질문이 나옵니다. "아니, 양성 선택할 때 자기 MHC랑 반응하는 놈을 살린다며? 근데 음성 선택 때는 자기 MHC랑 반응하는 놈을 죽인다며? 그럼 다 죽어야 하는 거 아냐?"
> 이 **Thymic Paradox**를 해결하는 기가 막힌 기전을 설명합니다.
>
> > [!INFO] PAGE 50: OT-I / TAP1 실험 (펩타이드가 다르다!)
> > 50페이지 실험을 보세요. 이 모순을 풀기 위한 실험입니다.
> > * **TAP1 KO 쥐:** 펩타이드 수송체가 고장 나서 MHC가 텅 비어 있습니다(Empty MHC). -> 세포 다 죽음 (Death by neglect).
> > * **Low affinity Peptide 추가:** 살짝만 붙는 펩타이드를 넣어줬더니 -> **생존 (Positive Selection)**.
> > * **High affinity Peptide 추가:** 꽉 붙는 펩타이드를 넣어줬더니 -> **사망 (Negative Selection)**.
> > * **결론:** 결국 **"펩타이드와의 결합 세기(Affinity)"**가 생사를 가릅니다.
>
> > [!IMPORTANT] PAGE 52-53: Thymoproteasome ($\beta$ 5t) - 비밀병기
> > 53페이지 그림이 그 해답의 결정타입니다. 피질 상피세포(cTEC)는 단백질을 자르는 가위가 다릅니다.
> > * **일반 세포:** 일반 프로테아좀을 씁니다.
> > * **cTEC (피질 세포):** **$\beta$5t**라는 특수 소단위체를 가진 **Thymoproteasome**을 씁니다.
> > * **기능:** 이 특수 가위는 단백질을 듬성듬성 잘라서 **'결합력이 약한(Low affinity)' 독특한 펩타이드**를 만듭니다.
> > * **해결:**
> >     1.  **Cortex:** cTEC이 만든 '약한 펩타이드'로 **양성 선택** (살살 달래서 살림).
> >     2.  **Medulla:** mTEC이나 DC가 만든 '진짜(강한) 펩타이드'로 **음성 선택** (세게 반응하는 놈 제거).
> >     * 이렇게 장소별로 **'메뉴(Peptide)'**를 다르게 해서 패러독스를 해결합니다.
> 
> >[!quote] 의문: PS에서 결합력이 약한 펩티드와 결합할 정도의 애면 NS에선 무조건 걸러지는거 아닌가?
> > - PS의 통과자는 **자기 MHC**를 인식할 수만 있으면 됨. 예컨대 자기 MHC+적당한 Peptide를 넣어버려서 **"약한 결합력"을 가지는 대신 MHC를 인식**할 수 있으면 통과.
> > - NS에서는 **결합력이 강한 Self peptide**를 제시해버려서, 조금이라도 자기 peptide와 결합할 수 있는 녀석은 모두 제거시키는거임.
> > - **결론: Peptide의 결합력 뿐만 아니라, 종류도 다르다**


> [!NOTE] Pages 54-60: 계통 결정 (Lineage Commitment) - CD4냐 CD8이냐
> DP 세포가 시험을 다 통과했습니다. 이제 옷을 갈아입어야죠. Helper(CD4)가 될지, Cytotoxic(CD8)이 될지 어떻게 정할까요?
>
> > [!IMPORTANT] PAGE 58: Kinetic Signaling Model (역동 신호 모델)
> > 58페이지 그림, **Singer 박사님** 이론입니다. 이게 최신 정설입니다. (야마!)
> > * **핵심:** "신호가 **끊기냐 지속되냐**가 운명을 가른다."
> > * **과정:**
> >     1.  양성 선택을 받으면 일단 **모든 DP 세포**는 **CD8 발현을 줄입니다(CD4+8lo)**.
> >     2.  **이때!**
> >         * **MHC II와 결합하던 놈:** CD4는 그대로 있으니 신호가 **계속(Continuous)** 들어옵니다 -> **CD4 T세포**가 됩니다.
> >         * **MHC I과 결합하던 놈:** CD8이 줄어드니까 신호가 **끊깁니다(Disrupted)**. 신호가 끊기면 **IL-7** 신호를 받아서 다시 CD8을 만들고 **CD8 T세포**가 됩니다.
> > * **요약:** 신호 지속(Continuous) = CD4, 신호 중단(Interrupted) + IL-7 구조 = CD8.
>
> > [!TIP] 💡 PAGE 59: Transcription Factor Switch (ThPOK vs Runx3)
> > 59페이지 그림의 분자 스위치를 외우세요. 서로 억제하는 관계입니다.
> > * **ThPOK:** **CD4**로 가는 열쇠. (T-Helper-POK).
> > * **Runx3:** **CD8**로 가는 열쇠.
> > * **기전:** ThPOK가 뜨면 Runx3를 누르고(CD4 됨), Runx3가 뜨면 ThPOK를 누릅니다(CD8 됨).


> [!NOTE] Pages 61-67: 졸업과 흉선 탈출 (Exit)
> 드디어 졸업입니다. 다 큰 T세포가 흉선을 떠나는 과정도 그냥 나가는 게 아닙니다.
>
> > [!INFO] PAGE 62: S1PR1과 탈출 기전
> > 62페이지 그림의 순서를 보세요.
> > 1.  **Foxo1 (전사인자)**이 활성화됩니다.
> > 2.  Foxo1이 **KLF2**를 켜고, KLF2가 **S1PR1 (스핑고신-1-인산 수용체)**을 발현시킵니다.
> > 3.  혈액 속에는 **S1P (Sphingosine-1-Phosphate)** 농도가 높습니다.
> > 4.  T세포의 S1PR1이 핏속의 S1P 냄새를 맡고 혈관으로 **Egress(탈출)**합니다.
> > * 참고: 흉선 안에서는 S1P 농도가 낮게 유지되어서 미성숙 세포가 못 나가게 막습니다.
>
> > [!INFO] PAGE 65-66: Treg (평화 유지군)
> > 마지막 보너스. 자기 반응성이 살짝 높은 애들(High affinity) 중 일부는 죽이지 않고 **Treg (조절 T세포)**로 스카우트합니다.
> > * **마커:** **FoxP3** (전사인자), **CD25**, **CD4**.
> > * **기능:** 사회(말초 조직)에 나가서 과도한 면역 반응을 억제합니다(Suppress). 사이토카인 뺏어먹기, 억제 물질 뿌리기 등으로 평화를 유지합니다.
, ',
    displayMath: [['$$', '$$'], ['\\[', '\\]']],
    processEscapes: true,
  },
  svg: {
    fontCache: 'global'
  }
};
</script>
<script type="text/javascript" id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-svg.js">
</script>

>[!quote] 공지
>본 자료의 저작권은 KAISTUDY에 있습니다.

---

> [!abstract]- 강의 요약: T세포의 발달 (T Cell Development)
>
> 이번 강의는 **Thymus**에 입학한 전구세포가 엄격한 **Selection**을 거쳐 정예 T세포로 졸업하는 과정을 다룹니다. 크게 **초기 발달(DN) -> 선택(DP) -> 계통 결정(SP) -> 졸업**의 흐름입니다.
>
> 1.  **Early Development (입학 및 진로 결정)**
>     * **장소:** Bone Marrow에서 온 전구세포가 **흉선(Thymus)**의 피질(Cortex)로 진입.
>     * **Notch 신호:** T세포가 되기 위한 필수 신호. (Notch1 없으면 B세포 됨).
>     * **DN 단계 (CD4-CD8-):** **CD44**와 **CD25** 마커 변화(DN1→DN2→DN3→DN4)를 통해 구분하며, **DN3** 단계에서 **$\beta$-Selection**을 통해 첫 번째 관문을 통과함.
>
> 2.  **$\beta$-Selection & Proliferation (중간 점검)**
>     * **Pre-TCR:** 기능적인 $\beta$ 사슬이 만들어졌는지 **Pre-T$\alpha$**와 결합해 확인.
>     * **결과:** 통과 시 **Allelic Exclusion**($\beta$ 유전자 재배열 중단), **대량 증식**, CD4/CD8 발현(DP 진입).
>
> 3.  **Selection Processes (졸업 시험: 98% 탈락)**
>     * **Positive Selection (Cortex):** **cTEC**이 제시하는 MHC를 **'적당히(Low affinity)'** 인식하면 생존. -> **MHC Restriction** 획득. (실패 시 Death by Neglect).
>     * **Negative Selection (Medulla):** **mTEC/DC**가 제시하는 자기 항원(Self-Ag)을 **'너무 세게(High affinity)'** 인식하면 제거. -> **Self-Tolerance** 획득.
>     * **Paradox 해결:** **Thymoproteasome($beta$ 5t)**이 피질에서 독특한 펩타이드를 만들어 양성 선택을 도움.
>
> 4.  **Lineage Commitment & Exit (진로 선택 및 졸업)**
>     * **CD4 vs CD8:** **Kinetic Signaling Model**에 따라 신호가 지속되면(Continuous) **CD4**, 끊기면(Interrupted) **CD8**이 됨. (전사인자 **ThPOK** vs **Runx3**의 길항 작용).
>     * **Exit:** **S1P-S1PR1** 상호작용을 통해 성숙한 T세포가 혈관으로 탈출.

> [!example]- 핵심 키워드 정리 (Key Terms & Concepts)
>
> ### 1. DN Stages & Checkpoints (족보)
> * **Notch1:** T세포 운명 결정의 핵심 (Notch on = T cell, Notch off = B cell).
> * **DN Markers:**
>     * **DN1:** `c-Kit++`, `CD44+`, `CD25-`
>     * **DN2:** `c-Kit++`, `CD44+`, **`CD25+`** (TCR 재배열 시작, Commitment).
>     * **DN3:** `c-Kit+`, **`CD44-`**, `CD25+` (**$\beta$-Selection**, Pre-TCR).
>     * **DN4:** `c-Kit-`, `CD44-`, **`CD25-`** (Proliferation, DP 준비).
> * **$\beta$-Selection:** DN3 단계. Pre-TCR 형성 확인 -> **Allelic Exclusion** 유도 -> **RAG 일시 중단** 및 증식.
>
> ### 2. Positive & Negative Selection (핵심 기전)
> * **Goldilocks Hypothesis:** 결합력이 너무 약해도(Neglect), 너무 강해도(Negative) 죽고, **적당해야(Positive)** 산다.
> * **MHC Restriction:** 흉선 환경(Thymus Stroma)에 의해 학습됨. (Chimera 실험: F1 골수 -> Parent B 흉선 이식 시 B형 MHC만 인식).
> * **H-Y Transgenic Mouse:**
>     * 수컷(Male): H-Y 항원 있음 -> 고친화력 -> **Negative Selection (Deletion)**.
>     * 암컷(Female): H-Y 항원 없음 -> 적당한 친화력 -> **Positive Selection (CD8 SP 생존)**.
> * **THEMIS:** 양성 선택 시 TCR 신호 감도 조절(Dampening by SHP-1).
> * **AIRE (AutoImmune Regulator):** 수질(mTEC)에서 췌장, 갑상선 등 **TSA(조직 특이 항원)**를 강제 발현시켜 자가반응성 T세포 제거. (결핍 시 자가면역질환).
> * **Thymoproteasome ($\beta$5t):** cTEC 특이적. 저친화력 펩타이드 생성 -> 양성 선택 유도.
>
> ### 3. Lineage Commitment (CD4 vs CD8)
> * **Kinetic Signaling Model (Singer):**
>     * MHC II 결합 -> CD8 down -> 신호 **지속(Continuous)** -> **CD4** 분화 (**ThPOK**).
>     * MHC I 결합 -> CD8 down -> 신호 **중단(Disrupted)** -> IL-7 신호 -> **CD8** 재발현 및 분화 (**Runx3**).
>
> ### 4. Graduation (Exit)
> * **S1PR1 & S1P:** 흉선 성숙 완료 시 **Foxo1 -> KLF2 -> S1PR1** 발현. 혈액 내 높은 S1P 농도를 따라 흉선 탈출(Egress).

---

> [!NOTE] Pages 1-5: T세포 발달의 개요와 흉선의 해부학적 구조
> 자, 먼저 숲을 보고 나무를 봅시다. T세포가 어디서 태어나서 어디로 가는지, 그 '학교'의 구조가 어떻게 생겨먹었는지부터 잡고 갑니다.
>
> > [!INFO] PAGE 2: 흉선의 퇴화 (Involution)
> > 2페이지 상단의 그림을 보세요. 아기 때(기어갈 때)는 흉선이 빵빵하죠? 그런데 나이 들수록(지팡이 짚을 때) 어떻게 됩니까? 쪼그라듭니다.
> > * **지방화(Fatty degeneration):** 나이가 들면 흉선 실질이 지방으로 대체되면서 T세포 생산 능력이 떨어집니다. 이게 노인 면역 저하의 원인 중 하나예요.
> > * **발달 타임라인:** 그림 아래쪽을 보면, **Bone Marrow(골수)**에서 온 전구세포가 **DN(Double Negative)** → **DP(Double Positive)** → **SP(Single Positive)** 단계로 성숙해가는 과정이 보이죠? 이 용어들, 오늘 지겹게 들을 거니 지금 눈에 익히세요.
>
> > [!INFO] PAGE 4: 흉선의 구조와 이동 경로 (Traffic)
> > 4페이지 그림 (a), (b), (c)를 같이 봅니다. T세포는 가만히 앉아서 크는 게 아니라, 흉선 안을 '이동'하면서 교육받습니다.
> > * **구조 (바깥 -> 안쪽):**
> >     1.  **Capsule (피막):** 껍데기.
> >     2.  **Subcapsular Cortex (피막하 피질):** 전구세포가 처음 들어와서 증식하는 곳.
> >     3.  **Cortex (피질/겉질):** 그림 (a)에서 진하게 염색된 부분. 여기서 **DN3, DN4, DP** 단계가 진행됩니다. **Positive Selection(양성선택)**의 주무대죠.
> >     4.  **Corticomedullary Junction:** 피질과 수질의 경계. 혈관(Blood vessel)이 여기로 들어옵니다. 전구세포도 여기로 들어오고, 다 큰 놈도 여기로 나갑니다.
> >     5.  **Medulla (수질/속질):** 그림 (a)에서 밝은 부분. **SP** 단계, **Negative Selection(음성선택)**이 일어납니다.
> > * **이동 경로 (화살표 보세요):** 혈관 타고 **CM Junction**으로 진입 -> **Subcapsular Cortex**로 이동 -> 다시 안쪽 **Cortex**로 진입 -> **Medulla** -> **Exit**. 이 동선을 기억해야 단계별 위치 문제를 맞춥니다.
>
> > [!INFO] PAGE 5: 흉선 상피세포 (Stroma)
> > T세포 혼자 크는 게 아닙니다. '선생님' 역할을 하는 상피세포들이 있어요.
> > * **cTECs (Cortical Thymic Epithelial Cells):** 피질에 있는 선생님. **Positive Selection** 담당.
> > * **mTECs (Medullary Thymic Epithelial Cells):** 수질에 있는 선생님. **Negative Selection** 담당.
> > * 이 세포들이 뭘 발현하느냐에 따라 T세포의 운명이 갈립니다.

> [!NOTE] Pages 6-9: 초기 발달과 Notch 신호 (운명의 갈림길)
> 흉선에 들어왔다고 무조건 T세포가 되는 게 아닙니다. "너 T세포 할래, B세포 할래?"를 결정하는 결정적인 신호가 있습니다. 여기서 **'야마(족보)'** 나옵니다.
>
> > [!IMPORTANT] PAGE 7: Notch Signaling (족보 포인트)
> > 7페이지 그림에 **"NOTCH"**라고 대문짝만하게 박혀 있고 **별표(야마)** 쳐져 있죠? 이거 무조건 나옵니다.
> > * **핵심:** 조혈모세포(HSC)가 흉선에 왔을 때, **Notch 신호**를 받아야만 T세포가 됩니다.
> > * **실험 증거 (텍스트 보세요):**
> >     1.  **Notch1 과발현(Overexpression):** 골수(Bone Marrow)에서도 T세포가 생겨버림 (원래는 B세포가 생겨야 함).
> >     2.  **Notch1 제거(Knockout):** 흉선(Thymus)인데도 T세포 대신 B세포가 생겨버림.
> > * **결론:** **"Notch = T cell lineage commitment"**. Notch가 있으면 T세포, 없으면 B세포입니다. (그림에서 B세포 쪽으로 가는 화살표에는 Notch 신호가 없는 걸 확인하세요!)
>
> > [!TIP] 💡 PAGE 8: OP9-DL1 실험 데이터 해석 (기출)
> > 이 데이터 해석하는 문제 자주 나옵니다. 8페이지 그림 뜯어봅시다.
> > * **실험 셋업:**
> >     * **OP9 세포:** 기질세포(Stromal cell).
> >     * **DL1 (Delta-like 1):** **Notch의 Ligand(리간드)**입니다. 즉, DL1이 있어야 Notch 신호를 줄 수 있습니다.
> > * **결과 그래프 (FACS Plot):**
> >     * **왼쪽 (Notch1 -/-):** Notch 수용체를 없앤 쥐. 흉선에 넣었는데도 **B세포(CD19+)**만 잔뜩 생깁니다. T세포는 안 생겨요.
> >     * **오른쪽 (Control):** 정상. T세포(Thy1+)가 잘 생깁니다.
> >     * **아래쪽 (OP9-DL1 배양):** 배양 접시에 **DL1(Notch 리간드)**을 깔아줬더니 줄기세포가 **DN1 -> DN2 -> DN3**로 쑥쑥 큽니다. (그림의 숫자 44, 25는 CD44, CD25 마커를 뜻함. 뒤에서 자세히 다룸).
> > * **한마디로:** 흉선 환경(Notch Ligand)이 없으면 T세포는 절대 못 만든다!

> [!NOTE] Pages 10-14: DN 단계의 세분화와 TCR 운명 결정 (Race)
> 자, 이제 **DN(Double Negative)** 단계를 현미경으로 들여다볼 시간입니다.
> 10페이지 그림과 11페이지 표, **이거 시험에 나옵니다.** 멍하니 "DN이구나" 하고 넘어가는 순간 유급입니다.
> DN 세포는 표면에 **CD4**도 없고 **CD8**도 없죠? 그럼 뭘로 구분하냐? 바로 **CD44**와 **CD25**입니다. 이 마커 변화를 외워야 합니다.
>
> > [!IMPORTANT] PAGE 10-11: DN1 ~ DN4 단계별 마커 (족보 테이블)
> > 11페이지 표를 보세요. **c-Kit (CD117)**, **CD44**, **CD25** 이 세 가지 마커의 변화 흐름을 잡아야 합니다.
> >
> > * **DN1 (Early):**
> >     * **마커:** `c-Kit++`, `CD44+`, `CD25-`
> >     * **특징:** 아직 흉선으로 이사 오는 중이거나 막 도착한 상태입니다. 아직 T세포로 완전히 결정되지 않아서(Multipotent), NK세포나 수지상세포(DC)로 빠질 수도 있는 시기입니다.
> >
> > * **DN2 (Commitment & Gene Rearrangement):**
> >     * **마커:** `c-Kit++`, `CD44+`, `CD25+` (**CD25가 양성으로 바뀜!**)
> >     * **핵심:** 여기서 **TCR 유전자 재배열($\gamma, \delta, \beta$)**이 시작됩니다. 그리고 7페이지에서 봤던 **Notch 신호**가 가장 강력하게 작용해서 "나는 이제 죽어도 T세포다"라고 **Commitment(계통 결정)**를 박는 시기입니다.
> >
> > * **DN3 ($\beta$-Selection Checkpoint):**
> >     * **마커:** `c-Kit+`, `CD44-`, `CD25+` (**CD44가 음성으로 바뀜!**)
> >     * **핵심:** 가장 중요합니다. 여기서 **$\beta$-selection**이 일어납니다. 즉, "TCR $\beta$ 사슬을 제대로 만들었니?" 검사하는 단계입니다. 통과 못 하면? 죽습니다(Apoptosis). Pre-TCR이 발현되는 시기이기도 하죠.
> >
> > * **DN4 (Pre-DP):**
> >     * **마커:** `c-Kit low/-`, `CD44-`, `CD25-` (**둘 다 음성!**)
> >     * **특징:** $\beta$-selection 통과했으니 기분 좋아서 미친듯이 **증식(Proliferation)**합니다. 그리고 이제 **$\alpha$ 사슬 재배열**을 준비하면서 **DP(Double Positive)** 단계로 넘어갑니다.
>
> > [!INFO] PAGE 13: TCR의 구조 ($\alpha\beta$ vs $\gamma\delta$)
> > 그림을 보세요. T세포는 두 종류의 수용체 중 하나를 가집니다.
> > * **$\alpha\beta$ TCR:** 우리 몸 T세포의 95% 이상. 적응면역의 주역이죠.
> > * **$\gamma\delta$ TCR:** 5% 미만. 주로 점막(Mucosa)이나 피부에 박혀서 선천면역처럼 작용합니다.
> > * 구조적으로 둘 다 **V(Variable)** 영역과 **C(Constant)** 영역이 있고, 세포막에 박혀 있죠? 옆에 **CD3 복합체($\epsilon, \delta, \gamma, \zeta$)**가 붙어있는 것도 똑같습니다. (CD3 없으면 신호 전달 못 합니다.)
>
> > [!TIP] 💡 PAGE 14: 확률 게임 (The Race Model)
> > 14페이지 텍스트를 씹어먹어 봅시다. 왜 $\alpha\beta$ T세포가 압도적으로 많을까요?
> > **"확률(Probability)"** 싸움입니다.
> > * **규칙:** DN2~DN3 단계에서 $\gamma, \delta, \beta$ 유전자 재배열이 동시에 시작됩니다(경주 시작!).
> > * **$\gamma\delta$ T세포가 되려면:** $\gamma$ 사슬과 $\delta$ 사슬 **두 개가 모두** 성공적으로 재배열되어야 합니다. (이벤트 2개 필요)
> > * **$\alpha\beta$ (정확히는 Pre-TCR) T세포가 되려면:** $\beta$ 사슬 **하나만** 성공하면 일단 멈추고($\beta$-selection), 증식한 뒤에 나중에 $\alpha$를 만듭니다. (이벤트 1개 필요)
> > * **결론:** 1개만 성공하면 되는 $\beta$ 쪽이 2개를 다 성공해야 하는 $\gamma\delta$보다 확률적으로 훨씬 유리합니다. 그래서 3배 이상 $\alpha\beta$ 쪽으로 많이 가는 겁니다.

> [!NOTE] Pages 15-20: $\gamma\delta$ T세포와 운명의 관문 ($\beta$-Selection)
> 자, 확률 게임에서 밀린 **$\gamma\delta$ T세포** 이야기 잠깐 하고, T세포 발달사에서 가장 중요한 **$\beta$-Selection**으로 넘어갑니다. 집중하세요.
>
> > [!INFO] PAGE 15: 태아 시기의 파동 (Waves)
> > 15페이지 그래프 보세요. X축이 **태아 발생일(Days of gestation)**입니다.
> > * **14~15일경:** 까만 선(**$\gamma\delta$ Thymocytes**)이 먼저 확 치솟습니다. 태아 때는 $\gamma\delta$가 먼저 만들어져요. 왜? 만들기 쉬우니까요. (단순하잖아)
> > * **출생(Birth) 이후:** 파란 선(**$\alpha\beta$ Thymocytes**)이 역전해서 압도적으로 많아집니다. 성인의 T세포 중 $\gamma\delta$는 **0.5%**밖에 안 됩니다.
>
> > [!INFO] PAGE 16: $\gamma\delta$ T세포의 마이웨이
> > 이놈들은 $\alpha\beta$와는 가는 길이 다릅니다. **"DP(Double Positive) 단계"를 안 거칩니다.**
> > * **특징 3가지 (외우세요):**
> >     1.  흉선을 나갈 때 **DN(CD4-CD8-)** 상태로 나갑니다. (쿨하게 나감)
> >     2.  **MHC 제한**이 없습니다. 이상한 항원(Lipid 등)을 인식해요.
> >     3.  주로 **점막(Mucosa)이나 피부(Skin)**로 가서 박혀 있습니다. 선천면역(Innate)처럼 최전방 방어선 역할을 하죠.
>
> > [!IMPORTANT] PAGE 18-19: $\beta$-Selection (생사가 걸린 검문소)
> > 18페이지 그림에 빨간 박스로 **$\beta$-selection** 표시돼 있죠? 별표 다섯 개 치세요. DN3 단계에서 일어나는 가장 결정적인 사건입니다.
> > * **상황:** $\beta$ 사슬 재배열을 끝냈습니다. 근데 이게 제대로 만들어졌는지 어떻게 알까요? 짝꿍인 $\alpha$ 사슬은 아직 안 만들었는데?
> > * **해결책 (Pre-TCR):** 그래서 **Pre-T$\alpha$**라는 가짜(Surrogate) $\alpha$ 사슬을 붙여봅니다. 이게 $\beta$ 사슬이랑 잘 붙어서 세포막에 뜨면 "합격" 신호가 터집니다.
> > * **신호의 결과 (4가지 기전 - 시험 나옵니다):**
> >     1.  **Stop $\beta$-rearrangement (Allelic Exclusion):** "하나 성공했으면 됐어. 다른 쪽 염색체 $\beta$ 유전자는 건드리지 마." (단일 특이성 보장)
> >     2.  **Proliferation (증식):** "성공한 놈이니까 복제해!" 세포 수가 폭발적으로 늘어납니다. (DN4 단계)
> >     3.  **Start $\alpha$-rearrangement:** "자, 이제 진짜 짝꿍($\alpha$) 만들자."
> >     4.  **Expression of CD4/CD8:** "이제 옷 입자." DP 단계로 넘어갑니다.
>
> > [!TIP] 💡 PAGE 20: RAG 발현의 파동 (기출)
> > 20페이지 아래쪽 그래프 보세요. **RAG(Recombination Activating Gene)** 효소 수치가 오르락내리락하죠?
> > * **1차 피크 (DN2~3):** $\beta$ 사슬 자르느라 RAG가 높습니다.
> > * **급격한 감소 (DN3~4):** $\beta$-selection 통과 후 **증식(Proliferation)**할 때는 RAG를 끕니다. (세포 분열 중에 DNA 자르면 큰일 나니까요. 이거 중요합니다!)
> > * **2차 피크 (DP):** 증식 끝나고 $\alpha$ 사슬 자르려니 다시 RAG가 올라갑니다. 이 흐름을 이해해야 그래프 문제 풉니다.

> [!NOTE] Pages 21-26: 양성 선택과 음성 선택의 서막 (지옥의 훈련소)
> 자, 유전자 재배열도 끝났고 $\beta$-selection도 통과해서 DP(Double Positive)가 됐습니다. 이제부터 진짜 '고시'가 시작됩니다.
> 23페이지 수치를 보세요. **98%가 죽습니다.** 단 2%만 살아남는 지옥의 훈련소, 그 원리를 파헤쳐 봅시다.
>
> > [!INFO] PAGE 22: 노벨상 수상자 (Doherty & Zinkernagel)
> > 이 아저씨들 얼굴 보고 지나가지 마세요. 이분들이 **MHC Restriction(MHC 제한)** 개념을 발견해서 노벨상 탔습니다.
> > * **핵심 개념 (외우세요):**
> >     * **Positive Selection (양성 선택):** 자기 MHC를 **'적당히(Low affinity)'** 인식할 줄 아는 놈만 살립니다. -> 결과: **MHC Restriction** 획득.
> >     * **Negative Selection (음성 선택):** 자기 MHC+자기 펩타이드에 **'너무 세게(High affinity)'** 반응하는 놈은 죽입니다. -> 결과: **Self-Tolerance(자기 관용)** 획득.
> > * 즉, **"너무 무관심해도 죽고(Neglect), 너무 집착해도 죽는다(Negative)."** 적당한 놈만 사는 겁니다. (Goldilocks hypothesis)
>
> > [!IMPORTANT] PAGE 25: MHC Restriction 증명 실험 (야마/기출)
> > **이 실험 100% 시험 나옵니다.** 별표 다섯 개 치세요. 방사선 조사 쥐(Chimera) 실험입니다.
> > 논리를 단계별로 따라오세요.
> > 1.  **준비물:**
> >     * **(A x B) F1 쥐:** 유전적으로 MHC A형과 B형을 둘 다 가짐.
> >     * **Strain B 쥐:** MHC B형만 가짐. (흉선을 제공할 대리모)
> > 2.  **실험 과정:**
> >     * Strain B 쥐에 방사선을 쏴서 자기 면역세포를 다 죽이고, **(A x B) F1의 골수(Stem cells)**를 이식합니다.
> >     * 그럼 F1 유전자를 가진 T세포가 **Strain B의 흉선(Thymus)**에서 교육받고 자라겠죠?
> > 3.  **결과 (핵심):**
> >     * 다 큰 T세포를 꺼내서 바이러스 감염된 세포를 죽이게 했더니, **Strain B 세포는 죽이는데(Killing), Strain A 세포는 못 죽입니다(No killing).**
> > 4.  **결론 (Interpretation):**
> >     * T세포의 **유전자**는 A, B 둘 다 가지고 있었지만, **흉선 학교가 B형**이라서 **"B형 MHC 보는 법"만 배웠다**는 겁니다.
> >     * 즉, **"MHC Restriction은 유전자가 아니라 흉선 환경(Thymus Environment)에 의해 학습된다."** 이게 정답입니다.
>
> > [!INFO] PAGE 26: 선택의 장소 (Cortex vs Medulla)
> > 그림의 위치와 비율을 보세요.
> > * **Cortex (피질):** 여기서 **Positive Selection**이 주로 일어납니다. 담당 교관은 **cTEC**입니다.
> > * **Death by Neglect (90~96%):** 그림 오른쪽 보세요. 대부분의 세포는 자기 MHC를 아예 인식 못 해서 여기서 그냥 **굶어 죽습니다(Apoptosis)**. 억울하게 죽는 게 아니라 무능해서 죽는 겁니다.
> > * **Medulla (수질):** 살아남은 애들이 여기로 와서 **Negative Selection**을 받습니다. 담당 교관은 **mTEC, DC(수지상세포)**입니다. 여기서 자기 몸 공격할 미친 놈들을 걸러냅니다.

> [!NOTE] Pages 27-33: MHC 제한과 H-Y 형질전환 마우스 실험 (실험 데이터 해석의 꽃)
> 자, 앞서 배운 MHC Restriction과 Negative Selection 이론을 실제로 증명한 전설적인 실험이 나옵니다.
> **H-Y Transgenic Mouse 실험**은 면역학 실험 데이터 해석 문제의 '조상님'입니다. FACS(유세포 분석) 데이터를 읽을 줄 모르면 시험장에 들어갈 생각도 하지 마세요.
>
> > [!INFO] PAGE 28-29: 친화력 모델 (Goldilocks Hypothesis)
> > 28페이지 그림을 봅시다. T세포의 운명은 **"TCR이 자기 MHC+자기 펩타이드를 얼마나 세게 잡느냐(Affinity)"**에 달려 있습니다.
> > * **No Interaction (무반응):** 90~96%가 해당됩니다. 아예 인식을 못 하니 쓸모가 없죠? **Death by Neglect (방치되어 사망)**.
> > * **High Affinity (너무 강함):** 자기 몸을 공격할 놈들입니다. 위험하죠? **Negative Selection (음성 선택)**으로 제거(Apoptosis)됩니다.
> > * **Low/Intermediate Affinity (적당함):** "어? 이거 내 MHC네?" 하고 살짝 건드리는 정도. 이놈들만 **Positive Selection (양성 선택)**으로 살아남아 **SP(Single Positive)**가 됩니다.
> > * **핵심:** 너무 차가워도 안 되고, 너무 뜨거워도 안 됩니다. 딱 적당해야 합니다.
>
> > [!IMPORTANT] PAGE 30: H-Y Transgenic Mouse 실험 셋업 (족보)
> > 30페이지 실험 설계를 뜯어봅시다. 조건이 복잡하니 집중하세요.
> > * **H-Y 항원:** 수컷(Male)에만 있는 항원입니다. (Y염색체 유래). 즉, **수컷에게는 'Self'**이고, **암컷에게는 'None'**입니다.
> > * **Transgenic TCR:** 연구자가 조작해서 넣어준 TCR입니다. 이 TCR은 **H-Y 항원**을 **H-2D^b (MHC Class I)**에 얹어서 제시할 때만 알아봅니다.
> > * **실험군 4가지:**
> >     1.  **Female H2-D^b:** H-Y 항원 없음 (적당한 결합 예상 -> 양성 선택).
> >     2.  **Male H2-D^b:** H-Y 항원 있음 (너무 강한 결합 예상 -> 음성 선택).
> >     3.  **Female H2-D^d:** MHC 종류가 다름 (결합 안 됨 -> 무시).
>
> > [!TIP] 💡 PAGE 31-33: FACS 데이터 해석 (기출 포인트)
> > 33페이지 FACS Plot을 보세요. X축은 **CD8**, Y축은 **CD4**입니다. 이 그림 해석하는 게 시험 문제입니다.
> >
> > * **1. Female H2-D^b (가운데 그림):**
> >     * **상황:** H-Y 항원이 없으므로 TCR이 '적당히' MHC만 인식합니다.
> >     * **결과:** **CD8+ SP 세포(오른쪽 아래, 37%)**가 뙇 하고 존재합니다.
> >     * **해석:** **Positive Selection**이 정상적으로 일어나서 CD8 T세포로 분화했습니다. (MHC Class I은 CD8을 만드니까요).
> >
> > * **2. Male H2-D^b (왼쪽 그림):**
> >     * **상황:** 수컷이라 H-Y 항원이 쫙 깔려 있습니다. TCR이 자기 항원(H-Y)을 '너무 세게' 뭅니다.
> >     * **결과:** CD8+ SP가 거의 없고(2%), **CD8low** 상태로 찌그러져 있거나 죽었습니다.
> >     * **해석:** **Negative Selection (Deletion)**이 일어나서 다 죽어나간 겁니다. 자기 반응성 세포를 없애는 과정이죠.
> >
> > * **3. Female H2-D^d (오른쪽 그림):**
> >     * **상황:** MHC 유전자가 **D^d**입니다. 이 TCR은 **D^b**만 좋아합니다. 짝이 안 맞죠?
> >     * **결과:** SP 세포가 아예 없습니다(0~3%). DP 단계(오른쪽 위)에만 머물러 있죠?
> >     * **해석:** 인식을 못 하니 양성 선택을 못 받아서 **Death by Neglect** 당한 겁니다. **"MHC Restriction"**을 증명하는 결과죠.
> >
> > * **결론:** 이 세 가지 그림을 보고 "양성 선택", "음성 선택", "MHC 제한"을 각각 매칭할 수 있어야 합니다.


> [!NOTE] Pages 34-37: 양성 선택의 분자적 기전 (THEMIS의 등장)
> 단순히 "적당히 결합하면 산다"로 끝내면 의대 수업이 아니죠. 그 신호가 세포 안에서 구체적으로 어떻게 전달되는지, **THEMIS**라는 단백질을 중심으로 파고듭니다.
>
> > [!INFO] PAGE 35: Death by Neglect (무시당한 자의 최후)
> > 35페이지 텍스트 보세요. 양성 선택(Positive Selection)을 통과하지 못한 세포들은 **3~4일** 안에 생존 신호를 못 받아서 **Apoptosis(세포자멸사)**로 죽습니다.
> > * 왜 이렇게 많이 죽일까요? (이유 2가지)
> >     1.  **Cluttering 방지:** 아무것도 인식 못 하는 멍청한 세포가 몸을 돌아다니며 공간만 차지하는 걸 막기 위함.
> >     2.  **확률 높이기:** 진짜 항원을 만날 확률이 있는 놈들만 남겨놔야 면역 효율이 올라가니까요.
>
> > [!TIP] 💡 PAGE 37: THEMIS Signaling Pathway (신상 족보)
> > 37페이지 그림, **THEMIS** 박스에 별표(야마) 쳐져 있죠? 이게 비교적 최근에 밝혀진 **가슴샘 세포 특이적 신호 분자**입니다.
> > * **위치:** 그림을 보면 **TCR 신호 전달 경로(Lck -> ZAP70 -> LAT)** 사이에 딱 끼어 있습니다.
> > * **작동 기전 (Mechanism):**
> >     * THEMIS는 **GRB-2**를 통해 **SHP-1 (Phosphatase, 인산분해효소)**을 끌고 옵니다.
> >     * **SHP-1**은 신호를 **끄는(Dampening)** 역할을 하죠.
> >     * **결과:** TCR 신호가 너무 강하지 않게 적절히 조절해서, 약한 신호(Low affinity)에서도 세포가 "어? 이거 양성 선택 신호네?"라고 알아먹고 생존하도록 돕습니다.
> > * **한마디로:** **"Positive Selection을 가능하게 하는 신호 튜너(Tuner)"**입니다. 이거 없으면 양성 선택이 안 됩니다.


> [!NOTE] Pages 38-46: 음성 선택과 AIRE (내 몸을 지키는 그림자)
> 이제 수질(Medulla)로 넘어왔습니다. 여기서 가장 중요한 건 **AIRE (AutoImmune Regulator)**입니다. 이건 면역학 전체를 통틀어 가장 중요한 개념 중 하나입니다.
>
> > [!IMPORTANT] PAGE 40: mTEC과 수지상세포의 협동
> > 40페이지 그림을 보세요. 음성 선택(Negative Selection)은 누가 시킵니까?
> > * **주연:** **mTEC (수질 가슴샘 상피세포)**.
> > * **조연:** **Dendritic Cell (수지상세포)**. mTEC이 만든 항원을 주워먹고 대신 제시해주기도 합니다.
> > * 이 과정이 실패하면? 자기 반응성 세포가 나가서 **자가면역질환(Autoimmune disease)**을 일으킵니다. 대표적인 예가 **제1형 당뇨병(T1D)**이죠.
>
> > [!TIP] 💡 PAGE 44-46: AIRE와 TSA (자가면역의 핵심 기전)
> > 44페이지 텍스트 보세요. 흉선(Thymus)은 심장도 아니고 췌장도 아닌데, 어떻게 심장이나 췌장 세포를 공격할 놈을 미리 걸러낼까요?
> > * **TSA (Tissue-Specific Antigens):** 인슐린(췌장), 티로글로불린(갑상선) 같은 특정 조직 항원들을 말합니다.
> > * **AIRE의 역할 (핵심):** **mTEC**에만 있는 **AIRE 단백질**이 이 TSA 유전자들을 흉선에서 강제로 발현시킵니다. 일종의 **"전신 항원 미리보기 서비스(Shadow)"**를 제공하는 거죠.
> > * **분자 기전 (46페이지 그림 상세):**
> >     * AIRE는 닫혀 있는(Silenced) 염색질에 접근해서 **RNA Polymerase**를 끌고 옵니다.
> >     * 그림에 **Ac(아세틸화), Me(메틸화)** 보이죠? 후성유전학적(Epigenetic) 조절을 통해 꽁꽁 숨겨진 유전자를 억지로 읽어내는 겁니다.
> > * **결론:** AIRE가 고장 나면? 흉선에서 인슐린을 못 보여줍니다. -> 인슐린 공격하는 T세포가 살아서 나갑니다. -> **당뇨병** 걸립니다. (APECED 증후군)


> [!NOTE] Pages 47-53: 흉선의 역설 (Paradox)과 해결책
> 여기서 아주 날카로운 질문이 나옵니다. "아니, 양성 선택할 때 자기 MHC랑 반응하는 놈을 살린다며? 근데 음성 선택 때는 자기 MHC랑 반응하는 놈을 죽인다며? 그럼 다 죽어야 하는 거 아냐?"
> 이 **Thymic Paradox**를 해결하는 기가 막힌 기전을 설명합니다.
>
> > [!INFO] PAGE 50: OT-I / TAP1 실험 (펩타이드가 다르다!)
> > 50페이지 실험을 보세요. 이 모순을 풀기 위한 실험입니다.
> > * **TAP1 KO 쥐:** 펩타이드 수송체가 고장 나서 MHC가 텅 비어 있습니다(Empty MHC). -> 세포 다 죽음 (Death by neglect).
> > * **Low affinity Peptide 추가:** 살짝만 붙는 펩타이드를 넣어줬더니 -> **생존 (Positive Selection)**.
> > * **High affinity Peptide 추가:** 꽉 붙는 펩타이드를 넣어줬더니 -> **사망 (Negative Selection)**.
> > * **결론:** 결국 **"펩타이드와의 결합 세기(Affinity)"**가 생사를 가릅니다.
>
> > [!IMPORTANT] PAGE 52-53: Thymoproteasome ($\beta$ 5t) - 비밀병기
> > 53페이지 그림이 그 해답의 결정타입니다. 피질 상피세포(cTEC)는 단백질을 자르는 가위가 다릅니다.
> > * **일반 세포:** 일반 프로테아좀을 씁니다.
> > * **cTEC (피질 세포):** **$\beta$5t**라는 특수 소단위체를 가진 **Thymoproteasome**을 씁니다.
> > * **기능:** 이 특수 가위는 단백질을 듬성듬성 잘라서 **'결합력이 약한(Low affinity)' 독특한 펩타이드**를 만듭니다.
> > * **해결:**
> >     1.  **Cortex:** cTEC이 만든 '약한 펩타이드'로 **양성 선택** (살살 달래서 살림).
> >     2.  **Medulla:** mTEC이나 DC가 만든 '진짜(강한) 펩타이드'로 **음성 선택** (세게 반응하는 놈 제거).
> >     * 이렇게 장소별로 **'메뉴(Peptide)'**를 다르게 해서 패러독스를 해결합니다.
> 
> >[!quote] 의문: PS에서 결합력이 약한 펩티드와 결합할 정도의 애면 NS에선 무조건 걸러지는거 아닌가?
> > - PS의 통과자는 **자기 MHC**를 인식할 수만 있으면 됨. 예컨대 자기 MHC+적당한 Peptide를 넣어버려서 **"약한 결합력"을 가지는 대신 MHC를 인식**할 수 있으면 통과.
> > - NS에서는 **결합력이 강한 Self peptide**를 제시해버려서, 조금이라도 자기 peptide와 결합할 수 있는 녀석은 모두 제거시키는거임.
> > - **결론: Peptide의 결합력 뿐만 아니라, 종류도 다르다**


> [!NOTE] Pages 54-60: 계통 결정 (Lineage Commitment) - CD4냐 CD8이냐
> DP 세포가 시험을 다 통과했습니다. 이제 옷을 갈아입어야죠. Helper(CD4)가 될지, Cytotoxic(CD8)이 될지 어떻게 정할까요?
>
> > [!IMPORTANT] PAGE 58: Kinetic Signaling Model (역동 신호 모델)
> > 58페이지 그림, **Singer 박사님** 이론입니다. 이게 최신 정설입니다. (야마!)
> > * **핵심:** "신호가 **끊기냐 지속되냐**가 운명을 가른다."
> > * **과정:**
> >     1.  양성 선택을 받으면 일단 **모든 DP 세포**는 **CD8 발현을 줄입니다(CD4+8lo)**.
> >     2.  **이때!**
> >         * **MHC II와 결합하던 놈:** CD4는 그대로 있으니 신호가 **계속(Continuous)** 들어옵니다 -> **CD4 T세포**가 됩니다.
> >         * **MHC I과 결합하던 놈:** CD8이 줄어드니까 신호가 **끊깁니다(Disrupted)**. 신호가 끊기면 **IL-7** 신호를 받아서 다시 CD8을 만들고 **CD8 T세포**가 됩니다.
> > * **요약:** 신호 지속(Continuous) = CD4, 신호 중단(Interrupted) + IL-7 구조 = CD8.
>
> > [!TIP] 💡 PAGE 59: Transcription Factor Switch (ThPOK vs Runx3)
> > 59페이지 그림의 분자 스위치를 외우세요. 서로 억제하는 관계입니다.
> > * **ThPOK:** **CD4**로 가는 열쇠. (T-Helper-POK).
> > * **Runx3:** **CD8**로 가는 열쇠.
> > * **기전:** ThPOK가 뜨면 Runx3를 누르고(CD4 됨), Runx3가 뜨면 ThPOK를 누릅니다(CD8 됨).


> [!NOTE] Pages 61-67: 졸업과 흉선 탈출 (Exit)
> 드디어 졸업입니다. 다 큰 T세포가 흉선을 떠나는 과정도 그냥 나가는 게 아닙니다.
>
> > [!INFO] PAGE 62: S1PR1과 탈출 기전
> > 62페이지 그림의 순서를 보세요.
> > 1.  **Foxo1 (전사인자)**이 활성화됩니다.
> > 2.  Foxo1이 **KLF2**를 켜고, KLF2가 **S1PR1 (스핑고신-1-인산 수용체)**을 발현시킵니다.
> > 3.  혈액 속에는 **S1P (Sphingosine-1-Phosphate)** 농도가 높습니다.
> > 4.  T세포의 S1PR1이 핏속의 S1P 냄새를 맡고 혈관으로 **Egress(탈출)**합니다.
> > * 참고: 흉선 안에서는 S1P 농도가 낮게 유지되어서 미성숙 세포가 못 나가게 막습니다.
>
> > [!INFO] PAGE 65-66: Treg (평화 유지군)
> > 마지막 보너스. 자기 반응성이 살짝 높은 애들(High affinity) 중 일부는 죽이지 않고 **Treg (조절 T세포)**로 스카우트합니다.
> > * **마커:** **FoxP3** (전사인자), **CD25**, **CD4**.
> > * **기능:** 사회(말초 조직)에 나가서 과도한 면역 반응을 억제합니다(Suppress). 사이토카인 뺏어먹기, 억제 물질 뿌리기 등으로 평화를 유지합니다.
], ['\\(', '\\)']],
    displayMath: [['$$', '$$'], ['\\[', '\\]']],
    processEscapes: true,
  },
  svg: {
    fontCache: 'global'
  }
};
</script>
<script type="text/javascript" id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-svg.js">
</script>

>[!quote] 공지
>본 자료의 저작권은 KAISTUDY에 있습니다.

---

> [!abstract]- 강의 요약: T세포의 발달 (T Cell Development)
>
> 이번 강의는 **Thymus**에 입학한 전구세포가 엄격한 **Selection**을 거쳐 정예 T세포로 졸업하는 과정을 다룹니다. 크게 **초기 발달(DN) -> 선택(DP) -> 계통 결정(SP) -> 졸업**의 흐름입니다.
>
> 1.  **Early Development (입학 및 진로 결정)**
>     * **장소:** Bone Marrow에서 온 전구세포가 **흉선(Thymus)**의 피질(Cortex)로 진입.
>     * **Notch 신호:** T세포가 되기 위한 필수 신호. (Notch1 없으면 B세포 됨).
>     * **DN 단계 (CD4-CD8-):** **CD44**와 **CD25** 마커 변화(DN1→DN2→DN3→DN4)를 통해 구분하며, **DN3** 단계에서 **$\beta$-Selection**을 통해 첫 번째 관문을 통과함.
>
> 2.  **$\beta$-Selection & Proliferation (중간 점검)**
>     * **Pre-TCR:** 기능적인 $\beta$ 사슬이 만들어졌는지 **Pre-T$\alpha$**와 결합해 확인.
>     * **결과:** 통과 시 **Allelic Exclusion**($\beta$ 유전자 재배열 중단), **대량 증식**, CD4/CD8 발현(DP 진입).
>
> 3.  **Selection Processes (졸업 시험: 98% 탈락)**
>     * **Positive Selection (Cortex):** **cTEC**이 제시하는 MHC를 **'적당히(Low affinity)'** 인식하면 생존. -> **MHC Restriction** 획득. (실패 시 Death by Neglect).
>     * **Negative Selection (Medulla):** **mTEC/DC**가 제시하는 자기 항원(Self-Ag)을 **'너무 세게(High affinity)'** 인식하면 제거. -> **Self-Tolerance** 획득.
>     * **Paradox 해결:** **Thymoproteasome($beta$ 5t)**이 피질에서 독특한 펩타이드를 만들어 양성 선택을 도움.
>
> 4.  **Lineage Commitment & Exit (진로 선택 및 졸업)**
>     * **CD4 vs CD8:** **Kinetic Signaling Model**에 따라 신호가 지속되면(Continuous) **CD4**, 끊기면(Interrupted) **CD8**이 됨. (전사인자 **ThPOK** vs **Runx3**의 길항 작용).
>     * **Exit:** **S1P-S1PR1** 상호작용을 통해 성숙한 T세포가 혈관으로 탈출.

> [!example]- 핵심 키워드 정리 (Key Terms & Concepts)
>
> ### 1. DN Stages & Checkpoints (족보)
> * **Notch1:** T세포 운명 결정의 핵심 (Notch on = T cell, Notch off = B cell).
> * **DN Markers:**
>     * **DN1:** `c-Kit++`, `CD44+`, `CD25-`
>     * **DN2:** `c-Kit++`, `CD44+`, **`CD25+`** (TCR 재배열 시작, Commitment).
>     * **DN3:** `c-Kit+`, **`CD44-`**, `CD25+` (**$\beta$-Selection**, Pre-TCR).
>     * **DN4:** `c-Kit-`, `CD44-`, **`CD25-`** (Proliferation, DP 준비).
> * **$\beta$-Selection:** DN3 단계. Pre-TCR 형성 확인 -> **Allelic Exclusion** 유도 -> **RAG 일시 중단** 및 증식.
>
> ### 2. Positive & Negative Selection (핵심 기전)
> * **Goldilocks Hypothesis:** 결합력이 너무 약해도(Neglect), 너무 강해도(Negative) 죽고, **적당해야(Positive)** 산다.
> * **MHC Restriction:** 흉선 환경(Thymus Stroma)에 의해 학습됨. (Chimera 실험: F1 골수 -> Parent B 흉선 이식 시 B형 MHC만 인식).
> * **H-Y Transgenic Mouse:**
>     * 수컷(Male): H-Y 항원 있음 -> 고친화력 -> **Negative Selection (Deletion)**.
>     * 암컷(Female): H-Y 항원 없음 -> 적당한 친화력 -> **Positive Selection (CD8 SP 생존)**.
> * **THEMIS:** 양성 선택 시 TCR 신호 감도 조절(Dampening by SHP-1).
> * **AIRE (AutoImmune Regulator):** 수질(mTEC)에서 췌장, 갑상선 등 **TSA(조직 특이 항원)**를 강제 발현시켜 자가반응성 T세포 제거. (결핍 시 자가면역질환).
> * **Thymoproteasome ($\beta$5t):** cTEC 특이적. 저친화력 펩타이드 생성 -> 양성 선택 유도.
>
> ### 3. Lineage Commitment (CD4 vs CD8)
> * **Kinetic Signaling Model (Singer):**
>     * MHC II 결합 -> CD8 down -> 신호 **지속(Continuous)** -> **CD4** 분화 (**ThPOK**).
>     * MHC I 결합 -> CD8 down -> 신호 **중단(Disrupted)** -> IL-7 신호 -> **CD8** 재발현 및 분화 (**Runx3**).
>
> ### 4. Graduation (Exit)
> * **S1PR1 & S1P:** 흉선 성숙 완료 시 **Foxo1 -> KLF2 -> S1PR1** 발현. 혈액 내 높은 S1P 농도를 따라 흉선 탈출(Egress).

---

> [!NOTE] Pages 1-5: T세포 발달의 개요와 흉선의 해부학적 구조
> 자, 먼저 숲을 보고 나무를 봅시다. T세포가 어디서 태어나서 어디로 가는지, 그 '학교'의 구조가 어떻게 생겨먹었는지부터 잡고 갑니다.
>
> > [!INFO] PAGE 2: 흉선의 퇴화 (Involution)
> > 2페이지 상단의 그림을 보세요. 아기 때(기어갈 때)는 흉선이 빵빵하죠? 그런데 나이 들수록(지팡이 짚을 때) 어떻게 됩니까? 쪼그라듭니다.
> > * **지방화(Fatty degeneration):** 나이가 들면 흉선 실질이 지방으로 대체되면서 T세포 생산 능력이 떨어집니다. 이게 노인 면역 저하의 원인 중 하나예요.
> > * **발달 타임라인:** 그림 아래쪽을 보면, **Bone Marrow(골수)**에서 온 전구세포가 **DN(Double Negative)** → **DP(Double Positive)** → **SP(Single Positive)** 단계로 성숙해가는 과정이 보이죠? 이 용어들, 오늘 지겹게 들을 거니 지금 눈에 익히세요.
>
> > [!INFO] PAGE 4: 흉선의 구조와 이동 경로 (Traffic)
> > 4페이지 그림 (a), (b), (c)를 같이 봅니다. T세포는 가만히 앉아서 크는 게 아니라, 흉선 안을 '이동'하면서 교육받습니다.
> > * **구조 (바깥 -> 안쪽):**
> >     1.  **Capsule (피막):** 껍데기.
> >     2.  **Subcapsular Cortex (피막하 피질):** 전구세포가 처음 들어와서 증식하는 곳.
> >     3.  **Cortex (피질/겉질):** 그림 (a)에서 진하게 염색된 부분. 여기서 **DN3, DN4, DP** 단계가 진행됩니다. **Positive Selection(양성선택)**의 주무대죠.
> >     4.  **Corticomedullary Junction:** 피질과 수질의 경계. 혈관(Blood vessel)이 여기로 들어옵니다. 전구세포도 여기로 들어오고, 다 큰 놈도 여기로 나갑니다.
> >     5.  **Medulla (수질/속질):** 그림 (a)에서 밝은 부분. **SP** 단계, **Negative Selection(음성선택)**이 일어납니다.
> > * **이동 경로 (화살표 보세요):** 혈관 타고 **CM Junction**으로 진입 -> **Subcapsular Cortex**로 이동 -> 다시 안쪽 **Cortex**로 진입 -> **Medulla** -> **Exit**. 이 동선을 기억해야 단계별 위치 문제를 맞춥니다.
>
> > [!INFO] PAGE 5: 흉선 상피세포 (Stroma)
> > T세포 혼자 크는 게 아닙니다. '선생님' 역할을 하는 상피세포들이 있어요.
> > * **cTECs (Cortical Thymic Epithelial Cells):** 피질에 있는 선생님. **Positive Selection** 담당.
> > * **mTECs (Medullary Thymic Epithelial Cells):** 수질에 있는 선생님. **Negative Selection** 담당.
> > * 이 세포들이 뭘 발현하느냐에 따라 T세포의 운명이 갈립니다.

> [!NOTE] Pages 6-9: 초기 발달과 Notch 신호 (운명의 갈림길)
> 흉선에 들어왔다고 무조건 T세포가 되는 게 아닙니다. "너 T세포 할래, B세포 할래?"를 결정하는 결정적인 신호가 있습니다. 여기서 **'야마(족보)'** 나옵니다.
>
> > [!IMPORTANT] PAGE 7: Notch Signaling (족보 포인트)
> > 7페이지 그림에 **"NOTCH"**라고 대문짝만하게 박혀 있고 **별표(야마)** 쳐져 있죠? 이거 무조건 나옵니다.
> > * **핵심:** 조혈모세포(HSC)가 흉선에 왔을 때, **Notch 신호**를 받아야만 T세포가 됩니다.
> > * **실험 증거 (텍스트 보세요):**
> >     1.  **Notch1 과발현(Overexpression):** 골수(Bone Marrow)에서도 T세포가 생겨버림 (원래는 B세포가 생겨야 함).
> >     2.  **Notch1 제거(Knockout):** 흉선(Thymus)인데도 T세포 대신 B세포가 생겨버림.
> > * **결론:** **"Notch = T cell lineage commitment"**. Notch가 있으면 T세포, 없으면 B세포입니다. (그림에서 B세포 쪽으로 가는 화살표에는 Notch 신호가 없는 걸 확인하세요!)
>
> > [!TIP] 💡 PAGE 8: OP9-DL1 실험 데이터 해석 (기출)
> > 이 데이터 해석하는 문제 자주 나옵니다. 8페이지 그림 뜯어봅시다.
> > * **실험 셋업:**
> >     * **OP9 세포:** 기질세포(Stromal cell).
> >     * **DL1 (Delta-like 1):** **Notch의 Ligand(리간드)**입니다. 즉, DL1이 있어야 Notch 신호를 줄 수 있습니다.
> > * **결과 그래프 (FACS Plot):**
> >     * **왼쪽 (Notch1 -/-):** Notch 수용체를 없앤 쥐. 흉선에 넣었는데도 **B세포(CD19+)**만 잔뜩 생깁니다. T세포는 안 생겨요.
> >     * **오른쪽 (Control):** 정상. T세포(Thy1+)가 잘 생깁니다.
> >     * **아래쪽 (OP9-DL1 배양):** 배양 접시에 **DL1(Notch 리간드)**을 깔아줬더니 줄기세포가 **DN1 -> DN2 -> DN3**로 쑥쑥 큽니다. (그림의 숫자 44, 25는 CD44, CD25 마커를 뜻함. 뒤에서 자세히 다룸).
> > * **한마디로:** 흉선 환경(Notch Ligand)이 없으면 T세포는 절대 못 만든다!

> [!NOTE] Pages 10-14: DN 단계의 세분화와 TCR 운명 결정 (Race)
> 자, 이제 **DN(Double Negative)** 단계를 현미경으로 들여다볼 시간입니다.
> 10페이지 그림과 11페이지 표, **이거 시험에 나옵니다.** 멍하니 "DN이구나" 하고 넘어가는 순간 유급입니다.
> DN 세포는 표면에 **CD4**도 없고 **CD8**도 없죠? 그럼 뭘로 구분하냐? 바로 **CD44**와 **CD25**입니다. 이 마커 변화를 외워야 합니다.
>
> > [!IMPORTANT] PAGE 10-11: DN1 ~ DN4 단계별 마커 (족보 테이블)
> > 11페이지 표를 보세요. **c-Kit (CD117)**, **CD44**, **CD25** 이 세 가지 마커의 변화 흐름을 잡아야 합니다.
> >
> > * **DN1 (Early):**
> >     * **마커:** `c-Kit++`, `CD44+`, `CD25-`
> >     * **특징:** 아직 흉선으로 이사 오는 중이거나 막 도착한 상태입니다. 아직 T세포로 완전히 결정되지 않아서(Multipotent), NK세포나 수지상세포(DC)로 빠질 수도 있는 시기입니다.
> >
> > * **DN2 (Commitment & Gene Rearrangement):**
> >     * **마커:** `c-Kit++`, `CD44+`, `CD25+` (**CD25가 양성으로 바뀜!**)
> >     * **핵심:** 여기서 **TCR 유전자 재배열($\gamma, \delta, \beta$)**이 시작됩니다. 그리고 7페이지에서 봤던 **Notch 신호**가 가장 강력하게 작용해서 "나는 이제 죽어도 T세포다"라고 **Commitment(계통 결정)**를 박는 시기입니다.
> >
> > * **DN3 ($\beta$-Selection Checkpoint):**
> >     * **마커:** `c-Kit+`, `CD44-`, `CD25+` (**CD44가 음성으로 바뀜!**)
> >     * **핵심:** 가장 중요합니다. 여기서 **$\beta$-selection**이 일어납니다. 즉, "TCR $\beta$ 사슬을 제대로 만들었니?" 검사하는 단계입니다. 통과 못 하면? 죽습니다(Apoptosis). Pre-TCR이 발현되는 시기이기도 하죠.
> >
> > * **DN4 (Pre-DP):**
> >     * **마커:** `c-Kit low/-`, `CD44-`, `CD25-` (**둘 다 음성!**)
> >     * **특징:** $\beta$-selection 통과했으니 기분 좋아서 미친듯이 **증식(Proliferation)**합니다. 그리고 이제 **$\alpha$ 사슬 재배열**을 준비하면서 **DP(Double Positive)** 단계로 넘어갑니다.
>
> > [!INFO] PAGE 13: TCR의 구조 ($\alpha\beta$ vs $\gamma\delta$)
> > 그림을 보세요. T세포는 두 종류의 수용체 중 하나를 가집니다.
> > * **$\alpha\beta$ TCR:** 우리 몸 T세포의 95% 이상. 적응면역의 주역이죠.
> > * **$\gamma\delta$ TCR:** 5% 미만. 주로 점막(Mucosa)이나 피부에 박혀서 선천면역처럼 작용합니다.
> > * 구조적으로 둘 다 **V(Variable)** 영역과 **C(Constant)** 영역이 있고, 세포막에 박혀 있죠? 옆에 **CD3 복합체($\epsilon, \delta, \gamma, \zeta$)**가 붙어있는 것도 똑같습니다. (CD3 없으면 신호 전달 못 합니다.)
>
> > [!TIP] 💡 PAGE 14: 확률 게임 (The Race Model)
> > 14페이지 텍스트를 씹어먹어 봅시다. 왜 $\alpha\beta$ T세포가 압도적으로 많을까요?
> > **"확률(Probability)"** 싸움입니다.
> > * **규칙:** DN2~DN3 단계에서 $\gamma, \delta, \beta$ 유전자 재배열이 동시에 시작됩니다(경주 시작!).
> > * **$\gamma\delta$ T세포가 되려면:** $\gamma$ 사슬과 $\delta$ 사슬 **두 개가 모두** 성공적으로 재배열되어야 합니다. (이벤트 2개 필요)
> > * **$\alpha\beta$ (정확히는 Pre-TCR) T세포가 되려면:** $\beta$ 사슬 **하나만** 성공하면 일단 멈추고($\beta$-selection), 증식한 뒤에 나중에 $\alpha$를 만듭니다. (이벤트 1개 필요)
> > * **결론:** 1개만 성공하면 되는 $\beta$ 쪽이 2개를 다 성공해야 하는 $\gamma\delta$보다 확률적으로 훨씬 유리합니다. 그래서 3배 이상 $\alpha\beta$ 쪽으로 많이 가는 겁니다.

> [!NOTE] Pages 15-20: $\gamma\delta$ T세포와 운명의 관문 ($\beta$-Selection)
> 자, 확률 게임에서 밀린 **$\gamma\delta$ T세포** 이야기 잠깐 하고, T세포 발달사에서 가장 중요한 **$\beta$-Selection**으로 넘어갑니다. 집중하세요.
>
> > [!INFO] PAGE 15: 태아 시기의 파동 (Waves)
> > 15페이지 그래프 보세요. X축이 **태아 발생일(Days of gestation)**입니다.
> > * **14~15일경:** 까만 선(**$\gamma\delta$ Thymocytes**)이 먼저 확 치솟습니다. 태아 때는 $\gamma\delta$가 먼저 만들어져요. 왜? 만들기 쉬우니까요. (단순하잖아)
> > * **출생(Birth) 이후:** 파란 선(**$\alpha\beta$ Thymocytes**)이 역전해서 압도적으로 많아집니다. 성인의 T세포 중 $\gamma\delta$는 **0.5%**밖에 안 됩니다.
>
> > [!INFO] PAGE 16: $\gamma\delta$ T세포의 마이웨이
> > 이놈들은 $\alpha\beta$와는 가는 길이 다릅니다. **"DP(Double Positive) 단계"를 안 거칩니다.**
> > * **특징 3가지 (외우세요):**
> >     1.  흉선을 나갈 때 **DN(CD4-CD8-)** 상태로 나갑니다. (쿨하게 나감)
> >     2.  **MHC 제한**이 없습니다. 이상한 항원(Lipid 등)을 인식해요.
> >     3.  주로 **점막(Mucosa)이나 피부(Skin)**로 가서 박혀 있습니다. 선천면역(Innate)처럼 최전방 방어선 역할을 하죠.
>
> > [!IMPORTANT] PAGE 18-19: $\beta$-Selection (생사가 걸린 검문소)
> > 18페이지 그림에 빨간 박스로 **$\beta$-selection** 표시돼 있죠? 별표 다섯 개 치세요. DN3 단계에서 일어나는 가장 결정적인 사건입니다.
> > * **상황:** $\beta$ 사슬 재배열을 끝냈습니다. 근데 이게 제대로 만들어졌는지 어떻게 알까요? 짝꿍인 $\alpha$ 사슬은 아직 안 만들었는데?
> > * **해결책 (Pre-TCR):** 그래서 **Pre-T$\alpha$**라는 가짜(Surrogate) $\alpha$ 사슬을 붙여봅니다. 이게 $\beta$ 사슬이랑 잘 붙어서 세포막에 뜨면 "합격" 신호가 터집니다.
> > * **신호의 결과 (4가지 기전 - 시험 나옵니다):**
> >     1.  **Stop $\beta$-rearrangement (Allelic Exclusion):** "하나 성공했으면 됐어. 다른 쪽 염색체 $\beta$ 유전자는 건드리지 마." (단일 특이성 보장)
> >     2.  **Proliferation (증식):** "성공한 놈이니까 복제해!" 세포 수가 폭발적으로 늘어납니다. (DN4 단계)
> >     3.  **Start $\alpha$-rearrangement:** "자, 이제 진짜 짝꿍($\alpha$) 만들자."
> >     4.  **Expression of CD4/CD8:** "이제 옷 입자." DP 단계로 넘어갑니다.
>
> > [!TIP] 💡 PAGE 20: RAG 발현의 파동 (기출)
> > 20페이지 아래쪽 그래프 보세요. **RAG(Recombination Activating Gene)** 효소 수치가 오르락내리락하죠?
> > * **1차 피크 (DN2~3):** $\beta$ 사슬 자르느라 RAG가 높습니다.
> > * **급격한 감소 (DN3~4):** $\beta$-selection 통과 후 **증식(Proliferation)**할 때는 RAG를 끕니다. (세포 분열 중에 DNA 자르면 큰일 나니까요. 이거 중요합니다!)
> > * **2차 피크 (DP):** 증식 끝나고 $\alpha$ 사슬 자르려니 다시 RAG가 올라갑니다. 이 흐름을 이해해야 그래프 문제 풉니다.

> [!NOTE] Pages 21-26: 양성 선택과 음성 선택의 서막 (지옥의 훈련소)
> 자, 유전자 재배열도 끝났고 $\beta$-selection도 통과해서 DP(Double Positive)가 됐습니다. 이제부터 진짜 '고시'가 시작됩니다.
> 23페이지 수치를 보세요. **98%가 죽습니다.** 단 2%만 살아남는 지옥의 훈련소, 그 원리를 파헤쳐 봅시다.
>
> > [!INFO] PAGE 22: 노벨상 수상자 (Doherty & Zinkernagel)
> > 이 아저씨들 얼굴 보고 지나가지 마세요. 이분들이 **MHC Restriction(MHC 제한)** 개념을 발견해서 노벨상 탔습니다.
> > * **핵심 개념 (외우세요):**
> >     * **Positive Selection (양성 선택):** 자기 MHC를 **'적당히(Low affinity)'** 인식할 줄 아는 놈만 살립니다. -> 결과: **MHC Restriction** 획득.
> >     * **Negative Selection (음성 선택):** 자기 MHC+자기 펩타이드에 **'너무 세게(High affinity)'** 반응하는 놈은 죽입니다. -> 결과: **Self-Tolerance(자기 관용)** 획득.
> > * 즉, **"너무 무관심해도 죽고(Neglect), 너무 집착해도 죽는다(Negative)."** 적당한 놈만 사는 겁니다. (Goldilocks hypothesis)
>
> > [!IMPORTANT] PAGE 25: MHC Restriction 증명 실험 (야마/기출)
> > **이 실험 100% 시험 나옵니다.** 별표 다섯 개 치세요. 방사선 조사 쥐(Chimera) 실험입니다.
> > 논리를 단계별로 따라오세요.
> > 1.  **준비물:**
> >     * **(A x B) F1 쥐:** 유전적으로 MHC A형과 B형을 둘 다 가짐.
> >     * **Strain B 쥐:** MHC B형만 가짐. (흉선을 제공할 대리모)
> > 2.  **실험 과정:**
> >     * Strain B 쥐에 방사선을 쏴서 자기 면역세포를 다 죽이고, **(A x B) F1의 골수(Stem cells)**를 이식합니다.
> >     * 그럼 F1 유전자를 가진 T세포가 **Strain B의 흉선(Thymus)**에서 교육받고 자라겠죠?
> > 3.  **결과 (핵심):**
> >     * 다 큰 T세포를 꺼내서 바이러스 감염된 세포를 죽이게 했더니, **Strain B 세포는 죽이는데(Killing), Strain A 세포는 못 죽입니다(No killing).**
> > 4.  **결론 (Interpretation):**
> >     * T세포의 **유전자**는 A, B 둘 다 가지고 있었지만, **흉선 학교가 B형**이라서 **"B형 MHC 보는 법"만 배웠다**는 겁니다.
> >     * 즉, **"MHC Restriction은 유전자가 아니라 흉선 환경(Thymus Environment)에 의해 학습된다."** 이게 정답입니다.
>
> > [!INFO] PAGE 26: 선택의 장소 (Cortex vs Medulla)
> > 그림의 위치와 비율을 보세요.
> > * **Cortex (피질):** 여기서 **Positive Selection**이 주로 일어납니다. 담당 교관은 **cTEC**입니다.
> > * **Death by Neglect (90~96%):** 그림 오른쪽 보세요. 대부분의 세포는 자기 MHC를 아예 인식 못 해서 여기서 그냥 **굶어 죽습니다(Apoptosis)**. 억울하게 죽는 게 아니라 무능해서 죽는 겁니다.
> > * **Medulla (수질):** 살아남은 애들이 여기로 와서 **Negative Selection**을 받습니다. 담당 교관은 **mTEC, DC(수지상세포)**입니다. 여기서 자기 몸 공격할 미친 놈들을 걸러냅니다.

> [!NOTE] Pages 27-33: MHC 제한과 H-Y 형질전환 마우스 실험 (실험 데이터 해석의 꽃)
> 자, 앞서 배운 MHC Restriction과 Negative Selection 이론을 실제로 증명한 전설적인 실험이 나옵니다.
> **H-Y Transgenic Mouse 실험**은 면역학 실험 데이터 해석 문제의 '조상님'입니다. FACS(유세포 분석) 데이터를 읽을 줄 모르면 시험장에 들어갈 생각도 하지 마세요.
>
> > [!INFO] PAGE 28-29: 친화력 모델 (Goldilocks Hypothesis)
> > 28페이지 그림을 봅시다. T세포의 운명은 **"TCR이 자기 MHC+자기 펩타이드를 얼마나 세게 잡느냐(Affinity)"**에 달려 있습니다.
> > * **No Interaction (무반응):** 90~96%가 해당됩니다. 아예 인식을 못 하니 쓸모가 없죠? **Death by Neglect (방치되어 사망)**.
> > * **High Affinity (너무 강함):** 자기 몸을 공격할 놈들입니다. 위험하죠? **Negative Selection (음성 선택)**으로 제거(Apoptosis)됩니다.
> > * **Low/Intermediate Affinity (적당함):** "어? 이거 내 MHC네?" 하고 살짝 건드리는 정도. 이놈들만 **Positive Selection (양성 선택)**으로 살아남아 **SP(Single Positive)**가 됩니다.
> > * **핵심:** 너무 차가워도 안 되고, 너무 뜨거워도 안 됩니다. 딱 적당해야 합니다.
>
> > [!IMPORTANT] PAGE 30: H-Y Transgenic Mouse 실험 셋업 (족보)
> > 30페이지 실험 설계를 뜯어봅시다. 조건이 복잡하니 집중하세요.
> > * **H-Y 항원:** 수컷(Male)에만 있는 항원입니다. (Y염색체 유래). 즉, **수컷에게는 'Self'**이고, **암컷에게는 'None'**입니다.
> > * **Transgenic TCR:** 연구자가 조작해서 넣어준 TCR입니다. 이 TCR은 **H-Y 항원**을 **H-2D^b (MHC Class I)**에 얹어서 제시할 때만 알아봅니다.
> > * **실험군 4가지:**
> >     1.  **Female H2-D^b:** H-Y 항원 없음 (적당한 결합 예상 -> 양성 선택).
> >     2.  **Male H2-D^b:** H-Y 항원 있음 (너무 강한 결합 예상 -> 음성 선택).
> >     3.  **Female H2-D^d:** MHC 종류가 다름 (결합 안 됨 -> 무시).
>
> > [!TIP] 💡 PAGE 31-33: FACS 데이터 해석 (기출 포인트)
> > 33페이지 FACS Plot을 보세요. X축은 **CD8**, Y축은 **CD4**입니다. 이 그림 해석하는 게 시험 문제입니다.
> >
> > * **1. Female H2-D^b (가운데 그림):**
> >     * **상황:** H-Y 항원이 없으므로 TCR이 '적당히' MHC만 인식합니다.
> >     * **결과:** **CD8+ SP 세포(오른쪽 아래, 37%)**가 뙇 하고 존재합니다.
> >     * **해석:** **Positive Selection**이 정상적으로 일어나서 CD8 T세포로 분화했습니다. (MHC Class I은 CD8을 만드니까요).
> >
> > * **2. Male H2-D^b (왼쪽 그림):**
> >     * **상황:** 수컷이라 H-Y 항원이 쫙 깔려 있습니다. TCR이 자기 항원(H-Y)을 '너무 세게' 뭅니다.
> >     * **결과:** CD8+ SP가 거의 없고(2%), **CD8low** 상태로 찌그러져 있거나 죽었습니다.
> >     * **해석:** **Negative Selection (Deletion)**이 일어나서 다 죽어나간 겁니다. 자기 반응성 세포를 없애는 과정이죠.
> >
> > * **3. Female H2-D^d (오른쪽 그림):**
> >     * **상황:** MHC 유전자가 **D^d**입니다. 이 TCR은 **D^b**만 좋아합니다. 짝이 안 맞죠?
> >     * **결과:** SP 세포가 아예 없습니다(0~3%). DP 단계(오른쪽 위)에만 머물러 있죠?
> >     * **해석:** 인식을 못 하니 양성 선택을 못 받아서 **Death by Neglect** 당한 겁니다. **"MHC Restriction"**을 증명하는 결과죠.
> >
> > * **결론:** 이 세 가지 그림을 보고 "양성 선택", "음성 선택", "MHC 제한"을 각각 매칭할 수 있어야 합니다.


> [!NOTE] Pages 34-37: 양성 선택의 분자적 기전 (THEMIS의 등장)
> 단순히 "적당히 결합하면 산다"로 끝내면 의대 수업이 아니죠. 그 신호가 세포 안에서 구체적으로 어떻게 전달되는지, **THEMIS**라는 단백질을 중심으로 파고듭니다.
>
> > [!INFO] PAGE 35: Death by Neglect (무시당한 자의 최후)
> > 35페이지 텍스트 보세요. 양성 선택(Positive Selection)을 통과하지 못한 세포들은 **3~4일** 안에 생존 신호를 못 받아서 **Apoptosis(세포자멸사)**로 죽습니다.
> > * 왜 이렇게 많이 죽일까요? (이유 2가지)
> >     1.  **Cluttering 방지:** 아무것도 인식 못 하는 멍청한 세포가 몸을 돌아다니며 공간만 차지하는 걸 막기 위함.
> >     2.  **확률 높이기:** 진짜 항원을 만날 확률이 있는 놈들만 남겨놔야 면역 효율이 올라가니까요.
>
> > [!TIP] 💡 PAGE 37: THEMIS Signaling Pathway (신상 족보)
> > 37페이지 그림, **THEMIS** 박스에 별표(야마) 쳐져 있죠? 이게 비교적 최근에 밝혀진 **가슴샘 세포 특이적 신호 분자**입니다.
> > * **위치:** 그림을 보면 **TCR 신호 전달 경로(Lck -> ZAP70 -> LAT)** 사이에 딱 끼어 있습니다.
> > * **작동 기전 (Mechanism):**
> >     * THEMIS는 **GRB-2**를 통해 **SHP-1 (Phosphatase, 인산분해효소)**을 끌고 옵니다.
> >     * **SHP-1**은 신호를 **끄는(Dampening)** 역할을 하죠.
> >     * **결과:** TCR 신호가 너무 강하지 않게 적절히 조절해서, 약한 신호(Low affinity)에서도 세포가 "어? 이거 양성 선택 신호네?"라고 알아먹고 생존하도록 돕습니다.
> > * **한마디로:** **"Positive Selection을 가능하게 하는 신호 튜너(Tuner)"**입니다. 이거 없으면 양성 선택이 안 됩니다.


> [!NOTE] Pages 38-46: 음성 선택과 AIRE (내 몸을 지키는 그림자)
> 이제 수질(Medulla)로 넘어왔습니다. 여기서 가장 중요한 건 **AIRE (AutoImmune Regulator)**입니다. 이건 면역학 전체를 통틀어 가장 중요한 개념 중 하나입니다.
>
> > [!IMPORTANT] PAGE 40: mTEC과 수지상세포의 협동
> > 40페이지 그림을 보세요. 음성 선택(Negative Selection)은 누가 시킵니까?
> > * **주연:** **mTEC (수질 가슴샘 상피세포)**.
> > * **조연:** **Dendritic Cell (수지상세포)**. mTEC이 만든 항원을 주워먹고 대신 제시해주기도 합니다.
> > * 이 과정이 실패하면? 자기 반응성 세포가 나가서 **자가면역질환(Autoimmune disease)**을 일으킵니다. 대표적인 예가 **제1형 당뇨병(T1D)**이죠.
>
> > [!TIP] 💡 PAGE 44-46: AIRE와 TSA (자가면역의 핵심 기전)
> > 44페이지 텍스트 보세요. 흉선(Thymus)은 심장도 아니고 췌장도 아닌데, 어떻게 심장이나 췌장 세포를 공격할 놈을 미리 걸러낼까요?
> > * **TSA (Tissue-Specific Antigens):** 인슐린(췌장), 티로글로불린(갑상선) 같은 특정 조직 항원들을 말합니다.
> > * **AIRE의 역할 (핵심):** **mTEC**에만 있는 **AIRE 단백질**이 이 TSA 유전자들을 흉선에서 강제로 발현시킵니다. 일종의 **"전신 항원 미리보기 서비스(Shadow)"**를 제공하는 거죠.
> > * **분자 기전 (46페이지 그림 상세):**
> >     * AIRE는 닫혀 있는(Silenced) 염색질에 접근해서 **RNA Polymerase**를 끌고 옵니다.
> >     * 그림에 **Ac(아세틸화), Me(메틸화)** 보이죠? 후성유전학적(Epigenetic) 조절을 통해 꽁꽁 숨겨진 유전자를 억지로 읽어내는 겁니다.
> > * **결론:** AIRE가 고장 나면? 흉선에서 인슐린을 못 보여줍니다. -> 인슐린 공격하는 T세포가 살아서 나갑니다. -> **당뇨병** 걸립니다. (APECED 증후군)


> [!NOTE] Pages 47-53: 흉선의 역설 (Paradox)과 해결책
> 여기서 아주 날카로운 질문이 나옵니다. "아니, 양성 선택할 때 자기 MHC랑 반응하는 놈을 살린다며? 근데 음성 선택 때는 자기 MHC랑 반응하는 놈을 죽인다며? 그럼 다 죽어야 하는 거 아냐?"
> 이 **Thymic Paradox**를 해결하는 기가 막힌 기전을 설명합니다.
>
> > [!INFO] PAGE 50: OT-I / TAP1 실험 (펩타이드가 다르다!)
> > 50페이지 실험을 보세요. 이 모순을 풀기 위한 실험입니다.
> > * **TAP1 KO 쥐:** 펩타이드 수송체가 고장 나서 MHC가 텅 비어 있습니다(Empty MHC). -> 세포 다 죽음 (Death by neglect).
> > * **Low affinity Peptide 추가:** 살짝만 붙는 펩타이드를 넣어줬더니 -> **생존 (Positive Selection)**.
> > * **High affinity Peptide 추가:** 꽉 붙는 펩타이드를 넣어줬더니 -> **사망 (Negative Selection)**.
> > * **결론:** 결국 **"펩타이드와의 결합 세기(Affinity)"**가 생사를 가릅니다.
>
> > [!IMPORTANT] PAGE 52-53: Thymoproteasome ($\beta$ 5t) - 비밀병기
> > 53페이지 그림이 그 해답의 결정타입니다. 피질 상피세포(cTEC)는 단백질을 자르는 가위가 다릅니다.
> > * **일반 세포:** 일반 프로테아좀을 씁니다.
> > * **cTEC (피질 세포):** **$\beta$5t**라는 특수 소단위체를 가진 **Thymoproteasome**을 씁니다.
> > * **기능:** 이 특수 가위는 단백질을 듬성듬성 잘라서 **'결합력이 약한(Low affinity)' 독특한 펩타이드**를 만듭니다.
> > * **해결:**
> >     1.  **Cortex:** cTEC이 만든 '약한 펩타이드'로 **양성 선택** (살살 달래서 살림).
> >     2.  **Medulla:** mTEC이나 DC가 만든 '진짜(강한) 펩타이드'로 **음성 선택** (세게 반응하는 놈 제거).
> >     * 이렇게 장소별로 **'메뉴(Peptide)'**를 다르게 해서 패러독스를 해결합니다.
> 
> >[!quote] 의문: PS에서 결합력이 약한 펩티드와 결합할 정도의 애면 NS에선 무조건 걸러지는거 아닌가?
> > - PS의 통과자는 **자기 MHC**를 인식할 수만 있으면 됨. 예컨대 자기 MHC+적당한 Peptide를 넣어버려서 **"약한 결합력"을 가지는 대신 MHC를 인식**할 수 있으면 통과.
> > - NS에서는 **결합력이 강한 Self peptide**를 제시해버려서, 조금이라도 자기 peptide와 결합할 수 있는 녀석은 모두 제거시키는거임.
> > - **결론: Peptide의 결합력 뿐만 아니라, 종류도 다르다**


> [!NOTE] Pages 54-60: 계통 결정 (Lineage Commitment) - CD4냐 CD8이냐
> DP 세포가 시험을 다 통과했습니다. 이제 옷을 갈아입어야죠. Helper(CD4)가 될지, Cytotoxic(CD8)이 될지 어떻게 정할까요?
>
> > [!IMPORTANT] PAGE 58: Kinetic Signaling Model (역동 신호 모델)
> > 58페이지 그림, **Singer 박사님** 이론입니다. 이게 최신 정설입니다. (야마!)
> > * **핵심:** "신호가 **끊기냐 지속되냐**가 운명을 가른다."
> > * **과정:**
> >     1.  양성 선택을 받으면 일단 **모든 DP 세포**는 **CD8 발현을 줄입니다(CD4+8lo)**.
> >     2.  **이때!**
> >         * **MHC II와 결합하던 놈:** CD4는 그대로 있으니 신호가 **계속(Continuous)** 들어옵니다 -> **CD4 T세포**가 됩니다.
> >         * **MHC I과 결합하던 놈:** CD8이 줄어드니까 신호가 **끊깁니다(Disrupted)**. 신호가 끊기면 **IL-7** 신호를 받아서 다시 CD8을 만들고 **CD8 T세포**가 됩니다.
> > * **요약:** 신호 지속(Continuous) = CD4, 신호 중단(Interrupted) + IL-7 구조 = CD8.
>
> > [!TIP] 💡 PAGE 59: Transcription Factor Switch (ThPOK vs Runx3)
> > 59페이지 그림의 분자 스위치를 외우세요. 서로 억제하는 관계입니다.
> > * **ThPOK:** **CD4**로 가는 열쇠. (T-Helper-POK).
> > * **Runx3:** **CD8**로 가는 열쇠.
> > * **기전:** ThPOK가 뜨면 Runx3를 누르고(CD4 됨), Runx3가 뜨면 ThPOK를 누릅니다(CD8 됨).


> [!NOTE] Pages 61-67: 졸업과 흉선 탈출 (Exit)
> 드디어 졸업입니다. 다 큰 T세포가 흉선을 떠나는 과정도 그냥 나가는 게 아닙니다.
>
> > [!INFO] PAGE 62: S1PR1과 탈출 기전
> > 62페이지 그림의 순서를 보세요.
> > 1.  **Foxo1 (전사인자)**이 활성화됩니다.
> > 2.  Foxo1이 **KLF2**를 켜고, KLF2가 **S1PR1 (스핑고신-1-인산 수용체)**을 발현시킵니다.
> > 3.  혈액 속에는 **S1P (Sphingosine-1-Phosphate)** 농도가 높습니다.
> > 4.  T세포의 S1PR1이 핏속의 S1P 냄새를 맡고 혈관으로 **Egress(탈출)**합니다.
> > * 참고: 흉선 안에서는 S1P 농도가 낮게 유지되어서 미성숙 세포가 못 나가게 막습니다.
>
> > [!INFO] PAGE 65-66: Treg (평화 유지군)
> > 마지막 보너스. 자기 반응성이 살짝 높은 애들(High affinity) 중 일부는 죽이지 않고 **Treg (조절 T세포)**로 스카우트합니다.
> > * **마커:** **FoxP3** (전사인자), **CD25**, **CD4**.
> > * **기능:** 사회(말초 조직)에 나가서 과도한 면역 반응을 억제합니다(Suppress). 사이토카인 뺏어먹기, 억제 물질 뿌리기 등으로 평화를 유지합니다.
