# Chapter 2: Strength of Materials (SOM) — Complete Interview Ready Notes

> **कवर किए गए सवाल:** Part 1 (Conceptual Q.1 – Q.61) + Part 2 (Previous ESE Q.1 – Q.57) = **कुल 118 सवाल (Complete)**
>
> **इंटरव्यू टिप:** SOM सिविल इंजीनियरिंग की नींव है। इंटरव्यूअर यहाँ से **Stress-Strain Curve, I-Section, Shear Centre, Theories of Failure, Columns और Deflection** पर सीधे क्रॉस-क्वेश्चन पूछते हैं। हर जवाब पूरे वाक्यों में बोलें और 1 लाइन का Practical Example ज़रूर जोड़ें।

---

## Part 1: Conceptual Interview Questions (Q.1 – Q.61)

### Q.1 Hardness (कठोरता) जांचने के मुख्य tests कौन-से हैं?
**उत्तर:** सर, किसी सामग्री की सतह पर खरोंच या गड्ढे (indentation) के विरुद्ध प्रतिरोध को Hardness कहते हैं। इसे जांचने के दो मुख्य तरीके हैं: (a) **Scratch Test** (खरोंच परीक्षण — जैसे Mohs scale), और (b) **Indentation Test** (दबाकर निशान बनाने का परीक्षण — जैसे **Brinell, Rockwell और Vickers hardness tests**)।
* **Site Use:** धातुओं (स्टील) के लिए मुख्यतः **Brinell/Rockwell** और पत्थरों/खनिजों के लिए **Mohs Scratch Test** इस्तेमाल होता है।

### Q.2 Scratch hardness test और Indentation hardness test में मूलभूत अंतर क्या है?
**उत्तर:** सर, **Scratch Test** में एक नुकीले हीरे (loaded diamond) को सामग्री की सतह पर दबाकर खींचा जाता है ताकि खरोंच बने, और उस खरोंच की चौड़ाई या आवश्यक लोड से hardness निकाली जाती है। जबकि **Indentation Test** में एक मानक आकार की कठोर बॉल या कोन (indenter) को सतह पर सीधा दबाया जाता है और उससे बने गड्ढे की गहराई या व्यास से hardness मापी जाती है।

### Q.3 Anisotropic materials क्या होते हैं?
**उत्तर:** सर, वे सामग्री जिनके भौतिक और यांत्रिक गुण (जैसे Modulus of Elasticity $E$) एक ही बिंदु पर **अलग-अलग दिशाओं में अलग-अलग** होते हैं, उन्हें **Anisotropic Materials** कहते हैं।
* **Site Example:** **लकड़ी (Timber)** और **Composite materials (FRP)**—लकड़ी अपने रेशों (grains) की दिशा में बहुत मजबूत होती है, लेकिन रेशों के $90^\circ$ पर काफी कमज़ोर होती है।

### Q.4 Ductility (तन्यता) को कैसे मापा जाता है?
**उत्तर:** सर, किसी सामग्री (जैसे स्टील सरिया) पर **Tensile Test** करके उसके टूटने के बाद दो पैरामीटर्स से Ductility मापी जाती है: (1) **Percentage Elongation** (लंबाई में प्रतिशत वृद्धि), या (2) **Percentage Reduction in Cross-sectional Area** (टूटने की जगह पर क्षेत्रफल में प्रतिशत कमी)।
* **Cross-Q:** *Mild steel और TMT Fe 500D के लिए minimum percentage elongation कितना होना चाहिए?*
  **उत्तर:** सर, IS 1786 के अनुसार **Fe 500** के लिए कम से कम **12%**, और भूकंप के लिए ज़्यादा ductile **Fe 500D** के लिए कम से कम **16%** होना चाहिए।

### Q.5 एक Ideal Brittle Material का stress-strain curve कैसा होता है?
**उत्तर:** सर, Ideal brittle material (जैसे काँच या Cast Iron) का tension में stress-strain curve **बिल्कुल सीधी रेखा (straight line)** होता है और इसमें बिना किसी yielding या प्लास्टिक खिंचाव के **अचानक टूट (sudden fracture)** हो जाती है।

### Q.6 किस प्रकार की loading में Toughness (चिमड़ापन) बहुत ज़रूरी होती है?
**उत्तर:** सर, **Shock loading, Impact loading और Cyclic/Earthquake loading** में—क्योंकि ऐसे झटकों में सामग्री को बिना टूटे बहुत ज़्यादा ऊर्जा सोखनी पड़ती है।

### Q.7 Toughness को कैसे मापा जाता है?
**उत्तर:** सर, किसी सामग्री को धीरे-धीरे बढ़ते हुए लोड के तहत **टूटने (rupture/fracture) तक प्रति इकाई आयतन जितनी कुल ऊर्जा** लगती है (अर्थात् **पूरे Stress-Strain curve के नीचे का कुल क्षेत्रफल**), उसे **Modulus of Toughness** कहते हैं। लैब में Impact toughness को **Charpy** या **Izod Impact Test** से मापते हैं।

### Q.8 डिज़ाइन की दृष्टि से किसी material का सबसे महत्वपूर्ण गुण कौन-सा है?
**उत्तर:** सर, **Strength (सामर्थ्य)**, क्योंकि यही गुण सामग्री को बिना फेल या टूटे बाहरी लोड्स को सुरक्षित रूप से सहन करने में सक्षम बनाता है। (भूकंप क्षेत्रों में strength के साथ **ductility** भी उतनी ही ज़रूरी है)।

### Q.9 Nominal Stress (Engineering Stress) और True Stress में क्या अंतर है?
**उत्तर:** सर:
* **Nominal (Engineering) Stress:** लगाए गए लोड को नमूने के **प्रारंभिक क्षेत्रफल ($A_0$)** से भाग देना ($\sigma = \frac{P}{A_0}$)। आम इंजीनियरिंग डिज़ाइन में यही इस्तेमाल होता है।
* **True Stress:** लगाए गए लोड को उस क्षण के **वास्तविक घटे हुए क्षेत्रफल ($A_{\text{actual}}$)** से भाग देना ($\sigma_{\text{true}} = \frac{P}{A_{\text{actual}}}$)। Necking के बाद True stress हमेशा Nominal stress से ज़्यादा होता है।

### Q.10 रबर (Rubber) का stress-strain curve कैसा होता है और क्यों?
**उत्तर:** सर, नरम रबर में बहुत ज़्यादा खिंचाव (large strains) तक लोड कम ही रहता है क्योंकि उसकी मुड़ी हुई पॉलीमर चेन्स धीरे-धीरे सीधी होती हैं। लेकिन जब सभी चेन्स पूरी तरह खिंचकर सीधी हो जाती हैं, तो रबर अचानक बहुत ज़्यादा प्रतिरोध दिखाता है और **टूटने से ठीक पहले ग्राफ तेज़ी से ऊपर की ओर मुड़ जाता है**।

### Q.11 Offset Yield Stress क्या होता है?
**उत्तर:** सर, High-strength steel (जैसे HYSD/TMT या एल्युमिनियम) में Mild steel जैसा कोई स्पष्ट yield point नहीं दिखता। इसलिए ऐसे पदार्थों के लिए stress-strain curve पर **$0.2\%$ (0.002) strain** से प्रारंभिक स्पर्श रेखा (initial tangent) के समानांतर एक रेखा खींची जाती है—वह रेखा ग्राफ को जहाँ काटती है, उसे **Offset Yield Stress (या $0.2\%$ Proof Stress)** कहते हैं।

### Q.12 Proof Stress क्या होता है?
**उत्तर:** सर, वह stress जो किसी सामग्री में उसकी मूल लंबाई का एक तय स्थायी (non-proportional/permanent) विस्तार—जैसे **$0.1\%$ या $0.2\%$**—पैदा करने के लिए आवश्यक हो, उसे **Proof Stress** कहते हैं।

### Q.13 Rupture Strength क्या होती है?
**उत्तर:** सर, Stress-strain curve के बिल्कुल अंतिम **टूटने वाले बिंदु (fracture point)** के संगत stress को **Rupture Strength** कहते हैं ($\frac{\text{Rupture Load}}{\text{Original Area}}$)।

### Q.14 डिज़ाइन में सामान्यतः किस stress को सामग्री का अधिकतम स्वीकार्य stress माना जाता है?
**उत्तर:** सर, **Ductile materials** (जैसे स्टील) के लिए **Yield Stress ($f_y$)** को, क्योंकि इसके बाद संरचना में भारी स्थायी विरूपण (permanent deformation) होने लगता है। (जबकि **Brittle materials** जैसे कंक्रीट/कास्ट आयरन के लिए **Ultimate Strength** लेते हैं)।

### Q.15 Working Stress क्या होता है?
**उत्तर:** सर, वास्तविक सेवा (working) के दौरान सामग्री में जितनी अधिकतम सुरक्षित stress की अनुमति दी जाती है, उसे **Working Stress (Permissible Stress)** कहते हैं:
* Ductile material के लिए: $\text{Working Stress} = \frac{\text{Yield Stress}}{\text{Factor of Safety}}$
* Brittle material के लिए: $\text{Working Stress} = \frac{\text{Ultimate Strength}}{\text{Factor of Safety}}$

### Q.16 State of Simple Shear (Pure Shear) को परिभाषित कीजिए।
**उत्तर:** सर, जब किसी तत्व (element) पर केवल **shear stress ($\tau$)** लग रहा हो और कोई normal stress न हो, तो उसे Pure/Simple Shear कहते हैं। इसकी सबसे बड़ी विशेषता यह है कि इस तल से **$45^\circ$ पर झुके हुए तलों** पर शुद्ध **tensile stress ($+\tau$)** और शुद्ध **compressive stress ($-\tau$)** पैदा होते हैं—इसी कारण कंक्रीट बीम में support के पास **$45^\circ$ के diagonal tension (shear) cracks** आते हैं!

### Q.17 Uniaxial stress system में stress element की दो सबसे महत्वपूर्ण orientations कौन-सी हैं?
**उत्तर:** सर, $\theta = 0^\circ$ और $\theta = 45^\circ$।
* **$\theta = 0^\circ$ (Principal Plane):** यहाँ **Normal stress अधिकतम ($\sigma$)** और Shear stress शून्य होता है।
* **$\theta = 45^\circ$:** यहाँ **Shear stress अधिकतम ($\tau_{\max} = \sigma/2$)** होता है।

### Q.18 दो लंबवत (perpendicular) तलों पर लगने वाले maximum और minimum shear stress में क्या अंतर होता है?
**उत्तर:** सर, उनका संख्यात्मक मान (magnitude) बिल्कुल बराबर होता है, वे केवल अपने **चिह्न (sign — एक clockwise और दूसरा anticlockwise)** में एक-दूसरे से भिन्न होते हैं (Complementary shear stress)।

### Q.19 अधिकांश धातुओं (metals) के लिए Poisson's Ratio ($\mu$) का मान कितना होता है?
**उत्तर:** सर, अधिकांश धातुओं के लिए यह **$0.25$ से $0.42$** के बीच होता है (जैसे स्टील के लिए $0.3$, एल्युमिनियम $0.33$, और कॉर्क के लिए $0$)।

### Q.20 जब किसी पिंड पर एक से ज़्यादा दिशाओं में stress लग रहा हो, तो stress-strain संबंध कैसा होता है?
**उत्तर:** सर, तब किसी एक दिशा में stress और strain सीधे समानुपाती **नहीं** रहते (Generalized Hooke's Law: $\epsilon_x = \frac{\sigma_x}{E} - \mu\frac{\sigma_y}{E} - \mu\frac{\sigma_z}{E}$)। यानी **Poisson's effect** के कारण किसी दिशा में बिना stress लगे भी वहाँ **strain पैदा हो सकता है**।

### Q.21 Plane Strain की शर्तें (conditions) क्या होती हैं?
**उत्तर:** सर, यह बहुत लंबे structures (जैसे **Retaining wall, Gravity dam या Tunnel**) में लागू होती है जहाँ लंबाई ($z$-दिशा) में विरूपण शून्य होता है:
1. $z$-दिशा में normal strain शून्य हो ($\epsilon_z = 0$)।
2. $y\text{-}z$ और $z\text{-}x$ तलों में shear strains शून्य हों ($\gamma_{yz} = 0, \gamma_{zx} = 0$)।

### Q.22 Non-elastic (Plastic) strain के दौरान किया गया कार्य (work done) कहाँ जाता है?
**उत्तर:** सर, Elastic limit पार होने के बाद किया गया कार्य कणों के बीच के बंधन तोड़कर उन्हें एक-दूसरे के ऊपर फिसलाने (permanent slip/deformation) में खर्च होता है, और यह सोखी गई ऊर्जा सामग्री के अंदर **ऊष्मा (heat)** के रूप में बदल जाती है (जिसे वापस recover नहीं किया जा सकता)।

### Q.23 Strain Energy Principle का क्या महत्व है?
**उत्तर:** सर, Strain energy सिद्धांत (जैसे Castigliano's theorem) का उपयोग **static और dynamic (impact/shock) दोनों प्रकार के लोड्स** के तहत जटिल संरचनाओं के **deflection, slope और indeterminate forces** निकालने के लिए बड़े पैमाने पर किया जाता है।

### Q.24 Resilience से आप क्या समझते हैं?
**उत्तर:** सर, किसी सामग्री की **elastic limit के अंदर ऊर्जा सोखने (absorb करने)** और लोड हटाने पर उसे वापस लौटाने की क्षमता को **Resilience** कहते हैं। इसे प्रति इकाई आयतन strain energy ($\frac{\sigma^2}{2E}$) से मापा जाता है।

### Q.25 Modulus of Resilience (Proof Resilience) क्या होता है?
**उत्तर:** सर, जब सामग्री को ठीक उसकी **elastic limit (yield/proof stress)** तक लोड किया जाए, तो उस समय प्रति इकाई आयतन में संचित **अधिकतम recoverable strain energy** ($\frac{\sigma_y^2}{2E}$) को **Modulus of Resilience** कहते हैं। (यह stress-strain curve में elastic limit तक के त्रिभुज का क्षेत्रफल होता है)।

### Q.26 Impact loading में Impact Factor क्या होता है?
**उत्तर:** सर, जब कोई वजन $h$ ऊँचाई से अचानक किसी छड़ पर गिरता है, तो उसमें होने वाला विरूपण ($\delta_{\text{impact}}$) धीरे से रखे गए उसी वजन के विरूपण ($\delta_{\text{static}}$) से कई गुना ज़्यादा होता है। इन दोनों के अनुपात को **Impact Factor** कहते हैं:
$$\text{Impact Factor} = \frac{\delta_{\text{impact}}}{\delta_{\text{static}}} = 1 + \sqrt{1 + \frac{2h}{\delta_{\text{static}}}}$$
*(यदि $h = 0$ यानी अचानक रख दिया जाए — sudden loading — तो Impact factor ठीक **2** होता है!)*

### Q.27 Brittle और Ductile materials के failure में क्या अंतर है?
**उत्तर:** सर, **Brittle material** (जैसे कंक्रीट, कास्ट आयरन) बिना किसी खास खिंचाव या warning के सीधे कणों के अलग होने (**direct tensile separation**, लोड के $90^\circ$ पर) से अचानक टूट जाते हैं। जबकि **Ductile material** (जैसे Mild steel) में कण $45^\circ$ के तल पर आपस में फिसलते (**shear slip**) हैं और टूटने से पहले भारी **necking व elongation** (warning) दिखाई देती है।

### Q.28 Engineering में 'Failure' से आपका क्या तात्पर्य है?
**उत्तर:** सर, Failure का मतलब हमेशा टुकड़ों में टूटना ही नहीं होता—इंजीनियरिंग में इसका मतलब है **Fracture (टूट जाना — brittle में)** या **Yielding / Excessive deformation (अत्यधिक मुड़ जाना — ductile में)**, दोनों में से जो भी पहले हो जाए और संरचना इस्तेमाल लायक न रहे।

### Q.29 Brittle materials के लिए कौन-सी Failure Theory सबसे उपयुक्त है?
**उत्तर:** सर, **Maximum Principal Stress Theory (Rankine's Theory)**, क्योंकि brittle materials tension में कमज़ोर होते हैं और जैसे ही अधिकतम principal tensile stress उनकी ultimate tensile strength पर पहुँचता है, वे टूट जाते हैं।

### Q.30 Maximum Strain Energy Theory को Brittle materials पर क्यों नहीं लागू कर सकते?
**उत्तर:** सर, क्योंकि यह सिद्धांत मानता है कि सामग्री की elastic limit tension और compression दोनों में बराबर है। लेकिन Brittle materials (जैसे कंक्रीट व कास्ट आयरन) की **compressive strength उनकी tensile strength से बहुत ज़्यादा (5 से 10 गुना)** होती है।

### Q.31 Hydrostatic pressure के तहत Guest's (Maximum Shear Stress) Theory लागू क्यों नहीं होती?
**उत्तर:** सर, Hydrostatic स्थिति में तीनों दिशाओं में बराबर principal stresses ($\sigma_1 = \sigma_2 = \sigma_3 = p$) लगते हैं। Guest's theory के अनुसार $\tau_{\max} = \frac{\sigma_1 - \sigma_3}{2} = 0$ आता है—अर्थात् यह थ्योरी कहती है कि पदार्थ कभी फेल ही नहीं होगा! (हाइड्रोस्टैटिक कम्प्रेशन में तो फिर भी ठीक है, लेकिन **hydrostatic tension** में पदार्थ निश्चित रूप से टूट जाएगा, इसलिए यह थ्योरी वहाँ फेल हो जाती है)।

### Q.32 Beam के bending में किसी परत के deformation और Neutral Axis से उसकी दूरी ($y$) में क्या संबंध है?
**उत्तर:** सर, Bending में किसी परत का खिंचाव या दबना (**strain / deformation**) उसकी **Neutral Axis से दूरी ($y$) के सीधे समानुपाती** होता है ($\epsilon = \frac{y}{R}$)। इसलिए Neutral Axis पर strain शून्य होता है और सबसे बाहरी सतह (top और bottom fibre) पर अधिकतम होता है।

### Q.33 Beam की धुरी की वक्रता (Curvature) और Flexural Rigidity ($EI$) में क्या संबंध है?
**उत्तर:** सर, Bending equation $\frac{M}{I} = \frac{E}{R} \implies \frac{1}{R} = \frac{M}{EI}$ से स्पष्ट है कि किसी दिए गए moment के लिए beam की **Curvature ($1/R$), Flexural Rigidity ($EI$) के व्युत्क्रमानुपाती (inversely proportional)** होती है—अर्थात् $EI$ जितना ज़्यादा होगा, बीम उतनी ही कम झुकेगी।

### Q.34 Simple bending के नियम (जहाँ shear force को शून्य माना गया है) सामान्य beams के डिज़ाइन के लिए पर्याप्त क्यों माने जाते हैं?
**उत्तर:** सर, दो व्यावहारिक कारणों से: (1) लंबी सामान्य beams में shear के कारण होने वाली हल्की warping से longitudinal bending strain पर कोई खास असर नहीं पड़ता, और (2) अधिकांश लोडिंग स्थितियों में **अधिकतम Bending Moment ठीक वहीं आता है जहाँ Shear Force शून्य ($0$)** होता है।

### Q.35 Beam of Uniform Strength के कितने configurations संभव हैं?
**उत्तर:** सर, दो configurations संभव हैं: (a) **Uniform Width ($b$ constant, depth $d$ बदलती है)** — जैसे पुलों के गहरे girders या haunched beams, और (b) **Uniform Depth ($d$ constant, width $b$ बदलती है)** — जैसे गाड़ियों की **Leaf Spring**।

### Q.36 Beam of Uniform Strength की सबसे मुख्य विशेषता क्या है?
**उत्तर:** सर, इसकी पूरी लंबाई में हर cross-section पर **अधिकतम bending stress ($\sigma_{\max}$) एक बराबर** रहती है, जिससे सामग्री की कोई बर्बादी नहीं होती और बीम सबसे हल्की व किफायती बनती है।

### Q.37 Strain Compatibility के मानदंड (criteria) से आप क्या समझते हैं?
**उत्तर:** सर, जब कोई बीम दो अलग-अलग पदार्थों को मिलाकर बनाई जाए (जैसे **RCC या Timber-Steel Composite Beam**), तो दोनों पदार्थों के बीच मजबूत bond होने से **Neutral Axis से समान दूरी पर दोनों पदार्थों में Strain बराबर होना चाहिए** ($\epsilon_1 = \epsilon_2 \implies \frac{\sigma_1}{E_1} = \frac{\sigma_2}{E_2}$)। इसी को Strain Compatibility कहते हैं।

### Q.38 एक Composite Beam (Flitched Beam) का कुल Moment of Resistance कितना होता है?
**उत्तर:** सर, यदि दोनों पदार्थ आपस में मजबूती से जुड़े हों (shear connectors द्वारा), तो composite action के कारण उनका कुल Moment of Resistance दोनों के **अलग-अलग Moment of Resistance के योग से भी ज़्यादा** होता है।

### Q.39 Sandwich Beams क्या होती हैं?
**उत्तर:** सर, यह एक हल्की लेकिन बेहद मजबूत composite beam होती है जिसमें **ऊपर और नीचे बहुत मजबूत सामग्री की दो पतली परतें (faces)** होती हैं (जो bending tension व compression लेती हैं), और **बीच में बहुत हल्के मटेरियल का मोटा कोर (core — जैसे फोम या हनीकॉम्ब)** होता है जो दोनों परतों को दूर रखकर Moment of Inertia बढ़ाता है।
* **Site Use:** हवाई जहाज के पंख, आधुनिक प्री-फैब पैनल्स और हल्की छतों में।

### Q.40 Solid circular section पर Shear Stress का वितरण कैसा होता है?
**उत्तर:** सर, यह **Parabolic** होता है—किनारों पर शून्य और केंद्र (Neutral Axis) पर अधिकतम:
$$\tau_{\max} = \frac{4}{3} \tau_{\text{avg}} = 1.333\,\tau_{\text{avg}}$$
अर्थात् अधिकतम shear stress औसत shear stress से **$33.33\%$ ज़्यादा** होता है। (जबकि आयताकार सेक्शन में यह $1.5\,\tau_{\text{avg}}$ यानी $50\%$ ज़्यादा होता है)।

### Q.41 I-section के Web द्वारा कितना Shear Force उठाया जाता है?
**उत्तर:** सर, I-section में लगभग **85% से 95% कुल Shear Force** अकेला बीच का **Web** उठाता है:
$$F_{\text{web}} = \frac{t_w \cdot d}{3}(2 q_{\max} + q_{\min})$$
(जबकि ऊपर-नीचे के **Flanges** मुख्य रूप से **Bending Moment** उठाते हैं)।

### Q.42 Transverse loading वाली बीम के किसी fibre पर Principal Stress का मान कितना होता है?
**उत्तर:** सर, Transverse load से किसी बिंदु पर Bending stress ($f = \frac{M}{I}y$) और Shear stress ($q = \frac{FA\bar{y}}{Ib}$) दोनों लगते हैं। इन दोनों के संयोजन से पैदा होने वाले Principal Stresses होते हैं:
$$\sigma_{1,2} = \frac{f}{2} \pm \sqrt{\left(\frac{f}{2}\right)^2 + q^2}$$

### Q.43 Beams का Deflection निकालने के प्रमुख methods कौन-से हैं?
**उत्तर:** सर, मुख्य 5 तरीके हैं: (a) **Double Integration Method** (Macaulay's method), (b) **Moment-Area Method** (Mohr's theorems), (c) **Conjugate Beam Method**, (d) **Strain Energy Method (Castigliano's theorem)**, और (e) **Unit Load Method**।

### Q.44 Moment-Area Method को समझाइए। *(ESE 2016)*
**उत्तर:** सर, यह किसी एक विशेष बिंदु पर slope या deflection निकालने का बहुत तेज़ तरीका है (खासकर cantilever beams में)। इसके दो प्रमेय हैं:
1. **Mohr's First Theorem:** किन्हीं दो बिंदुओं $A$ और $B$ के बीच slope का अंतर ($\theta_B - \theta_A$), उन दोनों के बीच के **$M/EI$ diagram के क्षेत्रफल (area)** के बराबर होता है।
2. **Mohr's Second Theorem:** बिंदु $B$ का बिंदु $A$ के tangent से ऊर्ध्वाधर विचलन ($t_{B/A}$), $A$ और $B$ के बीच के **$M/EI$ diagram के क्षेत्रफल का बिंदु $B$ के अबाउट moment** होता है।

### Q.45 Moment-Rotation diagram क्या होता है?
**उत्तर:** सर, किसी बीम पर लगाए गए Bending Moment ($M$) और उसके कारण हुए घूर्णन ($\theta$) के बीच का ग्राफ **Moment-Rotation Diagram** कहलाता है। Elastic सीमा के अंदर इस ग्राफ के नीचे का त्रिभुजाकार क्षेत्रफल ($W = \frac{1}{2}M\theta$) बीम में संचित **Bending Strain Energy** को दर्शाता है।

### Q.46 Middle-Third Rule क्या होता है?
**उत्तर:** सर, किसी आयताकार (rectangular) नींव, पियर या डैम के आधार पर **कहीं भी Tension पैदा न हो** (पूरी सतह compression में रहे), इसके लिए eccentric axial load की क्रिया-रेखा आधार के **बीच के एक-तिहाई हिस्से ($e \le b/6$ या $d/6$)** के अंदर से गुज़रनी चाहिए।

### Q.47 $b \times d$ के आयताकार सेक्शन पर $e$ eccentricity से लगे अक्षीय बल $P$ के कारण किनारों पर अधिकतम व न्यूनतम stress कितनी होती है?
**उत्तर:** सर:
$$\sigma_{\max/\min} = \frac{P}{A} \pm \frac{P \cdot e}{Z} = \frac{P}{b d}\left(1 \pm \frac{6e}{d}\right)$$

### Q.48 Middle-Fourth Rule क्या होता है?
**उत्तर:** सर, किसी **ठोस गोलाकार (solid circular)** कॉलम या चिमनी के आधार पर बिना tension के केवल compression बनाए रखने के लिए लोड की क्रिया-रेखा व्यास के **बीच के एक-चौथाई हिस्से ($e \le D/8$, अर्थात् केंद्र से $D/4$ व्यास के वृत्त)** के अंदर रहनी चाहिए। इसे ही **Middle-Fourth Rule** कहते हैं।

### Q.49 Euler's Column Theory की मुख्य limitations (कमियाँ) क्या हैं?
**उत्तर:** सर: (a) यह केवल **बहुत लंबे (long/slender) columns** पर ही लागू होती है जो शुद्ध buckling से फेल होते हैं—यह **short या intermediate columns** पर लागू नहीं होती (वहाँ यह असल से बहुत ज़्यादा buckling load बता देती है); (b) यह केवल **critical buckling load** बताती है, और यह मानती है कि कॉलम 100% सीधा व लोड बिल्कुल केंद्र पर है (जो साइट पर कभी नहीं होता)।

### Q.50 Rankine's Formula का क्या महत्व है?
**उत्तर:** सर, **Rankine-Gordon Formula** ($\frac{1}{P_R} = \frac{1}{P_c} + \frac{1}{P_E}$) एक व्यावहारिक (empirical) सूत्र है जो **Crushing ($P_c$) और Buckling ($P_E$) दोनों** के प्रभाव को जोड़ता है—इसलिए यह **बहुत छोटे से लेकर मध्यम और बहुत लंबे—सभी प्रकार के columns/struts** के लिए लागू होता है।

### Q.51 Pure torsion के अधीन गोलाकार शाफ्ट में Shear Stress का वितरण कैसा होता है?
**उत्तर:** सर, Torsion equation $\frac{T}{J} = \frac{\tau}{r}$ के अनुसार shear stress केंद्र से दूरी ($r$) के सीधे समानुपाती (**Linear**) होता है—अर्थात् शाफ्ट के **केंद्र पर शून्य** और **बाहरी सतह पर अधिकतम**।
* **Site Concept:** इसी कारण बीच का मटेरियल ज़्यादा काम नहीं करता, और बराबर वजन के लिए **Hollow Circular Shaft**, Solid shaft से कहीं ज़्यादा मजबूत होता है।

### Q.52 Spring क्या होती है और इसके मुख्य उपयोग क्या हैं?
**उत्तर:** सर, **Spring** एक लचीला (elastic) यांत्रिक उपकरण है जो लोड लगने पर मुड़कर **Resilience (strain energy)** के रूप में ऊर्जा जमा करता है और लोड हटने पर उसे वापस छोड़ता है। इसका मुख्य उपयोग गाड़ियों और मशीनों में **झटके सोखने (shock absorption)**, कंपन रोकने और बल मापने में होता है।

### Q.53 Spring की Resilience और Stiffness क्या होती हैं?
**उत्तर:** सर, सुरक्षित stress सीमा के अंदर स्प्रिंग द्वारा ऊर्जा सोखने की क्षमता को **Resilience** कहते हैं; और स्प्रिंग में **इकाई विरूपण (unit deflection)** पैदा करने के लिए आवश्यक बल को **Stiffness ($k = W/\delta$)** कहते हैं।

### Q.54 किसी Spring के चुनाव या डिज़ाइन में कौन-से 3 गुण देखने चाहिए?
**उत्तर:** सर: (a) उसकी **ऊर्जा सोखने की क्षमता (resilience)**, (b) दिए गए लोड पर होने वाला **deflection/stiffness**, और (c) उसकी **natural frequency of vibration** (ताकि resonance न हो)।

### Q.55 Leaf Spring (कमानी) का क्या कार्य है?
**उत्तर:** सर, ट्रकों और बसों में लगने वाली **Leaf Spring** एक beam of uniform strength की तरह काम करती है—इसका मुख्य कार्य कम लोड पर भी **बड़ा deflection देकर सड़क के गड्ढों के झटके सोखना**, बिना स्प्रिंग में ज़्यादा bending stress पैदा किए।

### Q.56 Thin Shell (पतला सिलेंडर/गोला) किसे कहते हैं?
**उत्तर:** सर, यदि किसी बेलनाकार या गोलाकार दबाव बर्तन (pressure vessel/pipe) की दीवार की मोटाई ($t$), उसके अंदरूनी व्यास ($d$) के **$\frac{1}{15}$ से $\frac{1}{20}$ (या $\frac{1}{10}$ से कम)** हो, तो उसे **Thin Shell** कहते हैं (इसमें दीवार की मोटाई में stress एकसमान माना जाता है)।

### Q.57 आंतरिक दबाव (internal pressure) के अधीन Thin Cylinder में कौन-सी stresses पैदा होती हैं?
**उत्तर:** सर, मुख्यतः 3 stresses होती हैं:
1. **Circumferential / Hoop Tensile Stress:** $\sigma_h = \frac{pd}{2t}$ (अधिकतम — यही सिलेंडर को लंबाई में फाड़ती है)।
2. **Longitudinal Tensile Stress:** $\sigma_l = \frac{pd}{4t}$ (Hoop stress का ठीक आधा)।
3. **Radial Compressive Stress:** अंदर $p$ और बाहर $0$ (बहुत छोटी होने से thin cylinder में नज़रअंदाज़ कर देते हैं)।

### Q.58 Lame's Equation क्या है?
**उत्तर:** सर, **Thick Cylinders** (जैसे हाई-प्रेशर हाइड्रोलिक पाइप या तोप की नली) में दीवार की मोटाई के साथ radial और hoop stress बदलती रहती है, जिसे **Lame's Equations** से निकालते हैं:
$$p_r = \frac{b}{r^2} - a \quad (\text{Radial compressive}) \quad \text{और} \quad \sigma_\theta = \frac{b}{r^2} + a \quad (\text{Hoop tensile})$$
जहाँ $a$ और $b$ constants हैं जो अंदरूनी व बाहरी दबाव से निकाले जाते हैं।

### Q.59 एकसमान क्रॉस-सेक्शन वाली लटकी हुई छड़ में उसके अपने स्वयं के वजन (self-weight $W$) के कारण कितना elongation होता है?
**उत्तर:** सर, $\Delta = \frac{WL}{2AE} = \frac{\gamma L^2}{2E}$—अर्थात् यह उसके निचले सिरे पर लटके हुए बराबर वजन ($W$) के कारण होने वाले खिंचाव ($\frac{WL}{AE}$) का **ठीक आधा** होता है।

### Q.60 क्या Thermal Stress, cross-sectional area पर निर्भर करता है?
**उत्तर:** **नहीं सर**, यदि किसी छड़ को फैलने से पूरी तरह रोका जाए, तो उसमें पैदा होने वाला thermal stress $\sigma_{\text{th}} = E \alpha \Delta T$ होता है—जो केवल material ($E, \alpha$) और तापमान में बदलाव ($\Delta T$) पर निर्भर करता है, **area या लंबाई पर नहीं**। (हालाँकि कुल Thermal Force $F = \sigma_{\text{th}} \cdot A$, area पर निर्भर करता है)।

### Q.61 Inelastic Strain Energy से आप क्या समझते हैं?
**उत्तर:** सर, Elastic limit पार होने के बाद किसी सामग्री को **स्थायी रूप से विकृत (permanently deform)** करने में जो ऊर्जा खर्च होकर ऊष्मा के रूप में नष्ट हो जाती है और लोड हटाने पर वापस नहीं मिलती, उसे **Inelastic Strain Energy** कहते हैं।

---

## Part 2: Previous ESE Interview Questions (Q.1 – Q.57)

### Q.1 Moment of Momentum क्या होता है? *(ESE 2016)*
**उत्तर:** सर, इसे **Angular Momentum ($\vec{L}$)** भी कहते हैं। किसी घूर्णन अक्ष से $\vec{r}$ दूरी पर गतिमान कण के रेखीय संवेग ($\vec{p} = m\vec{v}$) और दूरी के सदिश गुणनफल ($\vec{L} = \vec{r} \times m\vec{v}$) को Moment of Momentum कहते हैं। इसके बदलने की दर बाहरी **Torque** के बराबर होती है।

### Q.2 Mild Steel का Stress-Strain Curve कैसा होता है? *(ESE 2016)*
**उत्तर:** सर, Mild Steel के stress-strain curve में 6 स्पष्ट चरण होते हैं:
1. **Proportional Limit:** यहाँ तक Hooke's Law ($\sigma \propto \epsilon$) लागू होता है (सीधी रेखा)।
2. **Elastic Limit:** यहाँ तक लोड हटाने पर छड़ पूरी तरह पुरानी लंबाई में लौट आती है।
3. **Upper & Lower Yield Points:** यहाँ बिना लोड बढ़ाए ही स्टील तेज़ी से खिंचने (**Yield plateau**) लगता है।
4. **Strain Hardening:** इसके बाद स्टील के क्रिस्टल दोबारा व्यवस्थित होकर और ज़्यादा लोड उठाते हैं, **Ultimate Tensile Strength (UTS)** तक।
5. **Necking:** UTS के बाद एक जगह से छड़ पतली होने लगती है और nominal stress गिरता है।
6. **Fracture Point:** अंत में **Cup-and-Cone** आकार में छड़ टूट जाती है।

### Q.3 Poisson's Ratio ($\mu$) क्या होता है? *(ESE 2016)*
**उत्तर:** सर, Elastic limit के अंदर किसी छड़ को खींचने पर उसकी चौड़ाई में होने वाली कमी (**Lateral Strain**) और लंबाई में होने वाली वृद्धि (**Longitudinal Strain**) के अनुपात को Poisson's Ratio कहते हैं:
$$\mu = -\frac{\text{Lateral Strain}}{\text{Longitudinal Strain}}$$
(माइनस चिह्न इसलिए क्योंकि दोनों strain विपरीत प्रकृति के होते हैं; इसका मान सैद्धांतिक रूप से $-1$ से $+0.5$, और इंजीनियरिंग मटेरियल्स में $0$ से $0.5$ के बीच होता है)।

### Q.4 Column और Strut में क्या अंतर है? *(ESE 2016)*
**उत्तर:** सर, दोनों ही **compression members** हैं:
* **Column (Stanchion/Post):** यह हमेशा **बिल्कुल सीधा खड़ा (vertical)** भारी compression member होता है जो इमारतों की छतों, बीम और पुलों का वजन नींव तक पहुँचाता है।
* **Strut:** यह अपेक्षाकृत छोटा और हल्का compression member है जो **किसी भी दिशा (क्षैतिज, तिरछा या खड़ा)** में हो सकता है—जैसे **Steel Roof Trusses** या गहरी खुदाई में साइड सपोर्ट देने वाले तिरछे/क्षैतिज ब्रेसिंग्स।

### Q.5 Slope-Deflection Method क्या होता है? *(ESE 2016)*
**उत्तर:** सर, यह indeterminate structures को हल करने का एक **Displacement (Stiffness) Method** है। इसमें joints के अज्ञात rotations ($\theta$) और displacements ($\Delta$) को unknowns मानकर हर member के सिरों के moments को उनके रूप में लिखा जाता है, और फिर joint equilibrium equations ($\Sigma M = 0$) से unknowns निकाल लिए जाते हैं।

### Q.6 Fixed Beam का Bending Moment Diagram (BMD) कैसा होता है? *(ESE 2016)*
**उत्तर:** सर, Fixed beam में दोनों सिरों पर **Hogging (negative)** और बीच में **Sagging (positive)** BM आता है:
* **मध्य में Point Load ($W$):** दोनों सिरों पर $-\frac{WL}{8}$ और बीच में $+\frac{WL}{8}$ (Point of contraflexure सिरों से $L/4$ पर)।
* **पूरी लंबाई पर UDL ($w$):** दोनों सिरों पर $-\frac{wL^2}{12}$ और बीच में $+\frac{wL^2}{24}$ (Point of contraflexure सिरों से $0.211 L$ पर)।

### Q.7 Column की विभिन्न support conditions और उनकी Effective Length ($L_{\text{eff}}$) क्या होती हैं? *(ESE 2016)*
**उत्तर:** सर, Euler के सिद्धांत के अनुसार 4 मानक स्थितियाँ हैं:
1. **दोनों सिरे Hinged/Pinned:** $L_{\text{eff}} = L$
2. **एक सिरा Fixed, दूसरा Free (Flagpole/Tank staging):** $L_{\text{eff}} = 2L$
3. **दोनों सिरे Fixed:** $L_{\text{eff}} = L/2 = 0.5L$ *(IS 456 में डिज़ाइन के लिए $0.65L$ लेते हैं)*
4. **एक सिरा Fixed, दूसरा Hinged:** $L_{\text{eff}} = L/\sqrt{2} = 0.707L$ *(IS 456 में $0.80L$)*।

### Q.8 Slenderness Ratio ($\lambda$) की परिभाषा क्या है? *(ESE 2016)*
**उत्तर:** सर, किसी कॉलम की **Effective Length ($L_{\text{eff}}$)** और उसके cross-section के **Minimum Radius of Gyration ($r_{\min} = \sqrt{I_{\min}/A}$)** के अनुपात को **Slenderness Ratio** ($\lambda = \frac{L_{\text{eff}}}{r_{\min}}$) कहते हैं। यह जितना ज़्यादा होगा, कॉलम के **buckling (मुड़ने)** का खतरा उतना ही ज़्यादा होगा।

### Q.9 Slenderness ratio को कौन-से मुख्य factors नियंत्रित करते हैं? *(ESE 2016)*
**उत्तर:** सर: (1) कॉलम की **वास्तविक लंबाई ($L$)**, (2) सिरों की **Support/End conditions** (जिनसे $L_{\text{eff}}$ तय होता है), और (3) कॉलम का **Cross-sectional आकार** (जिससे $r_{\min}$ तय होता है)।

### Q.10 एक समान लोड और मटेरियल होने पर Short Column और Long Column में से कौन पहले फेल होगा? *(ESE 2016)*
**उत्तर:** सर, **Long (Slender) Column पहले फेल होगा**, क्योंकि उसका slenderness ratio ज़्यादा होता है और Euler's buckling load ($P_E \propto \frac{1}{L_{\text{eff}}^2}$) कम हो जाता है—इसलिए वह सामग्री के crushing से काफी पहले ही **buckling** से मुड़कर फेल हो जाएगा।

### Q.11 Coefficient of Restitution ($e$) क्या होता है? *(ESE 2016)*
**उत्तर:** सर, दो पिंडों के आपस में टकराने (collision) के बाद उनके अलग होने के सापेक्ष वेग और टकराने से पहले पास आने के सापेक्ष वेग के अनुपात को Coefficient of Restitution कहते हैं:
$$e = \frac{|v_2 - v_1|}{|u_1 - u_2|}$$
इसका मान **$0$ (perfectly inelastic — दोनों चिपक जाएँ)** से लेकर **$1$ (perfectly elastic — ऊर्जा की कोई हानि नहीं)** तक होता है।

### Q.12 Young's Modulus of Elasticity ($E$) क्या होता है? *(ESE 2016)*
**उत्तर:** सर, Elastic limit के अंदर किसी सामग्री में **Longitudinal Stress और Longitudinal Strain के अनुपात** ($E = \frac{\sigma}{\epsilon}$) को Young's Modulus कहते हैं। यह सामग्री की **stiffness (कठोरता)** बताता है (Unit: $\text{N/m}^2$ या $\text{MPa/GPa}$)।

### Q.13 Steel और Concrete का Poisson's Ratio कितना होता है? *(ESE 2016)*
**उत्तर:** सर, **Steel** के लिए elastic range में **$0.30$** (और plastic range में $0.50$), तथा **Concrete** के लिए **$0.15$ से $0.20$** (या $0.1\text{–}0.2$) होता है।

### Q.14 Pressure और Stress में क्या अंतर है? *(ESE 2016)*
**उत्तर:** सर, भले ही दोनों की unit ($\text{N/m}^2$) एक है, लेकिन इनमें 4 बड़े अंतर हैं:
1. **Nature:** **Pressure** हमेशा बाहरी और सतह के लंबवत (normal compressive) होता है; **Stress** अंदरूनी प्रतिरोधी बल है जो tensile, compressive या shear (तिरछा) कुछ भी हो सकता है।
2. **Quantity:** Pressure एक **Scalar** है; Stress एक **Tensor** (दिशा और तल दोनों पर निर्भर) है।
3. **Medium:** Pressure मुख्यतः **Fluids** में; Stress मुख्यतः **Solids** में होता है।
4. **Measurement:** Pressure सीधे gauge से मापा जा सकता है; Stress को सीधे नहीं मापा जा सकता, बल्कि strain या force/area से गणना की जाती है।

### Q.15 किसी इमारत में Settlement क्यों होता है? *(ESE 2016)*
**उत्तर:** सर, इसके मुख्य 5 कारण हैं: (1) नीचे की मिट्टी का **कमज़ोर (low bearing capacity)** होना, (2) भराई की मिट्टी का **अधूरा compaction**, (3) मिट्टी में **नमी का बदलना** (जैसे Black cotton soil में सूखना-फूलना), (4) Saturated clay में समय के साथ **Consolidation**, और (5) नींव के पास बड़े पेड़ों की जड़ों द्वारा मिट्टी का पानी सोखना।

### Q.16 Strain का क्या अर्थ है? *(ESE 2016)*
**उत्तर:** सर, बाहरी बल लगने पर किसी वस्तु के आकार (लंबाई) में हुए बदलाव और उसकी मूल लंबाई के अनुपात को **Strain** कहते हैं ($\epsilon = \frac{\Delta L}{L}$)। यह एक **विमाहीन (dimensionless)** राशि है।

### Q.17 Homogeneous, Isotropic और Anisotropic में क्या अंतर है? *(ESE 2016)*
**उत्तर:** सर:
* **Homogeneous:** जिसके गुण पूरे पिंड में **हर बिंदु (position)** पर एक समान हों।
* **Isotropic:** जिसके गुण किसी एक बिंदु पर **हर दिशा (direction)** में एक समान हों (जैसे स्टील — केवल 2 स्वतंत्र elastic constants $E, \mu$)।
* **Anisotropic:** जिसके गुण एक ही बिंदु पर **अलग-अलग दिशाओं में अलग** हों (जैसे लकड़ी — 21 elastic constants)।

### Q.18 Shear Force और Bending Moment में क्या अंतर है? *(ESE 2016)*
**उत्तर:** सर, किसी बीम के किसी सेक्शन के एक तरफ (बाएँ या दाएँ) लगे सभी ऊर्ध्वाधर बलों के बीजगणितीय योग को **Shear Force ($V$)** कहते हैं (यह बीम को काटने की कोशिश करता है)। जबकि उन्हीं सभी बलों के उस सेक्शन के अबाउट आघूर्णों के योग को **Bending Moment ($M$)** कहते हैं (यह बीम को मोड़ने की कोशिश करता है)। दोनों का संबंध $V = \frac{dM}{dx}$ है।

### Q.19 हमें Strength of Materials पढ़ने की आवश्यकता क्यों है? *(ESE 2016)*
**उत्तर:** सर, ताकि हम यह सटीक गणना कर सकें कि किसी बीम, कॉलम या पुल पर लोड पड़ने पर उसके अंदर कितना stress और deflection आएगा—जिससे हम संरचना को **सुरक्षित (safe — गिरे नहीं)** और **किफायती (economical — फालतू भारी न बने)** डिज़ाइन कर सकें।

### Q.20 Shear Force (SF) और Bending Moment (BM) में क्या संबंध है? *(ESE 2016)*
**उत्तर:** सर, $V = \frac{dM}{dx}$ (अर्थात् BM ग्राफ का ढलान Shear Force देता है, और जहाँ **Shear Force अपना चिह्न बदलकर शून्य** होता है, वहाँ **Bending Moment अधिकतम** होता है)।

### Q.21 Hoop Stress क्या होती है? *(ESE 2016)*
**उत्तर:** सर, जब किसी गोल पाइप, पानी की टंकी या बॉयलर के अंदर से द्रव का दबाव लगता है, तो उसकी परिधि (circumference) के along जो **खिंचाव बल (circumferential tensile stress)** पैदा होता है और दीवार को फटने से रोकता है, उसे **Hoop Stress** ($\sigma_h = \frac{pd}{2t}$) कहते हैं।

### Q.22 Bending Stress क्या होती है और इसका I-section से क्या संबंध है? *(ESE 2015)*
**उत्तर:** सर, जब किसी बीम पर लोड पड़ता है और वह झुकती है, तो Neutral Axis के एक तरफ compression और दूसरी तरफ tension पैदा होता है—इसे **Bending Stress** कहते हैं ($\sigma_b = \frac{M}{I}y$)। यह Neutral Axis से दूरी ($y$) के साथ बढ़ती है और **सबसे ऊपर व नीचे के किनारों पर अधिकतम** होती है। I-section में ज़्यादातर स्टील ठीक इन्हीं ऊपरी व निचले किनारों (**flanges**) में रखा जाता है ताकि अधिकतम Bending Stress को आसानी से झेला जा सके।

### Q.23 Beams के लिए I-section का इतना ज़्यादा इस्तेमाल क्यों किया जाता है? *(ESE 2015)*
**उत्तर:** सर, क्योंकि Bending में सबसे ज़्यादा stress ऊपर और नीचे के किनारों पर आती है और बीच (Neutral Axis) में लगभग शून्य होती है। **I-section** में ज़्यादातर मटेरियल Neutral Axis से सबसे दूर **Flanges** में होता है—जिससे **कम वजन (कम स्टील) में अधिकतम Moment of Inertia ($I$) और Section Modulus ($Z$)** मिलता है, और बीच का पतला **Web** पूरा shear संभाल लेता है। इसलिए यह सबसे सस्ता और मजबूत बीम सेक्शन है।

### Q.24 विभिन्न Theories of Failure कौन-सी हैं? *(ESE 2015)*
**उत्तर:** सर, मुख्य 5 सिद्धांत हैं:
1. **Maximum Principal Stress Theory (Rankine)** — Brittle materials (Cast iron) के लिए बेस्ट।
2. **Maximum Shear Stress Theory (Guest / Tresca)** — Ductile materials के लिए (थोड़ा conservative)।
3. **Maximum Principal Strain Theory (St. Venant)** — आजकल कम उपयोग।
4. **Maximum Total Strain Energy Theory (Haigh)** — Ductile materials के लिए।
5. **Maximum Distortion Energy Theory (Von-Mises / Hencky)** — **Ductile materials (स्टील) के लिए सबसे सटीक और सबसे ज़्यादा इस्तेमाल होने वाली थ्योरी**।

### Q.25 Von-Mises Theory को समझाइए। *(ESE 2015)*
**उत्तर:** सर, इसे **Maximum Distortion (Shear Strain) Energy Theory** या **Octahedral Shear Stress Theory** भी कहते हैं। इसके अनुसार किसी जटिल 3D लोडिंग में कोई ductile सामग्री तब फेल (yield) होती है जब उसमें आकार बदलने वाली **distortion energy प्रति इकाई आयतन**, साधारण tensile test में yield point पर होने वाली distortion energy के बराबर हो जाए:
$$(\sigma_1 - \sigma_2)^2 + (\sigma_2 - \sigma_3)^2 + (\sigma_3 - \sigma_1)^2 \le 2\sigma_y^2$$
* **Site/Industry Use:** स्टील डिज़ाइन कोड्स (**IS 800**) और आधुनिक सॉफ्टवेयर्स (ANSYS/STAAD) में ductile metals के लिए यही सबसे सटीक मानी जाती है।

### Q.26 क्या Principal Stress शून्य (zero) हो सकता है? *(ESE 2015)*
**उत्तर:** **हाँ सर**, बिल्कुल हो सकता है! उदाहरण के लिए किसी साधारण **Uniaxial Tension** (केवल $x$-दिशा में खींचना) में $\sigma_1 = \sigma$ होता है, लेकिन बाकी दोनों principal stresses **$\sigma_2 = 0$ और $\sigma_3 = 0$** होते हैं।

### Q.27 Mohr-Coulomb Theory क्या होती है? *(ESE 2015)*
**उत्तर:** सर, यह उन सामग्रियों (जैसे **मिट्टी/Soil, कंक्रीट और चट्टान**) के लिए failure theory है जिनकी compressive strength उनकी tensile strength से बहुत ज़्यादा होती है। इसके अनुसार किसी तल पर फेलियर तब होता है जब shear stress, cohesion और normal stress से मिलने वाले घर्षण से बढ़ जाए: $\tau_f = c + \sigma \tan\phi$।

### Q.28 Euler's Buckling Theory को परिभाषित कीजिए। *(ESE 2015)*
**उत्तर:** सर, यह **लंबे और पतले (long/slender) columns** का critical buckling load निकालने का सिद्धांत है: $P_E = \frac{\pi^2 EI_{\min}}{L_{\text{eff}}^2}$। यह मानता है कि कॉलम शुरू में बिल्कुल सीधा, homogeneous, isotropic और elastic है, लोड बिल्कुल केंद्र पर लगा है, और फेलियर केवल **buckling** से होता है।

### Q.29 Hooke's Law क्या है? Brittle और Ductile failure surfaces कैसी दिखती हैं? *(ESE 2014, 2016)*
**उत्तर:** सर, **Hooke's Law** कहता है कि proportional limit के अंदर stress, strain के सीधे समानुपाती होता है ($\sigma = E \epsilon$)।
* **Failure Surfaces (Tension में):** **Brittle material** (Cast iron) लोड के $90^\circ$ पर एक **सपाट, खुरदरी और चमकदार (flat rough)** सतह पर टूटता है। जबकि **Ductile material** (Mild steel) में बीच में सपाट और किनारों पर $45^\circ$ तिरछी **Cup-and-Cone** आकृति की धुंधली सतह बनती है।

### Q.30 Stress Tensor को परिभाषित कीजिए और इसे Matrix रूप में लिखिए। *(ESE 2014, 2016)*
**उत्तर:** सर, किसी 3D पिंड के एक बिंदु पर 3 लंबवत तलों पर कुल **9 stress components** (3 normal और 6 shear) लगते हैं, जिन्हें बताने के लिए तल और दिशा—दोनों चाहिए। इसलिए Stress एक **2nd-order Tensor** है:
$$[\sigma] = \begin{bmatrix} \sigma_{xx} & \tau_{xy} & \tau_{xz} \\ \tau_{yx} & \sigma_{yy} & \tau_{yz} \\ \tau_{zx} & \tau_{zy} & \sigma_{zz} \end{bmatrix}$$
(चूँकि $\tau_{xy} = \tau_{yx}$ आदि होते हैं, इसलिए यह एक **symmetric matrix** है जिसमें केवल 6 स्वतंत्र components होते हैं)।

### Q.31 Centre of Gravity (CG) और Centroid में परिभाषा के आधार पर क्या अंतर है? *(ESE 2014)*
**उत्तर:** सर, **Centre of Gravity (CG)** किसी 3D ठोस वस्तु का वह बिंदु है जहाँ उसका पूरा **वजन/द्रव्यमान (mass/weight)** केंद्रित माना जाता है (यह density पर निर्भर करता है)। जबकि **Centroid** किसी 2D समतल आकृति (जैसे त्रिभुज, I-section) का शुद्ध **ज्यामितीय केंद्र (geometrical center)** है। (अगर वस्तु की density हर जगह एकसमान हो, तो CG और Centroid एक ही बिंदु पर होते हैं)।

### Q.32 Section Modulus ($Z$) क्या होता है? *(ESE 2014)*
**उत्तर:** सर, किसी क्रॉस-सेक्शन के Moment of Inertia ($I$) और Neutral Axis से सबसे बाहरी सतह की दूरी ($y_{\max}$) के अनुपात को **Section Modulus** ($Z = \frac{I}{y_{\max}}$) कहते हैं। चूँकि Moment of Resistance $M = \sigma \cdot Z$ होता है, इसलिए $Z$ सीधे बीम की **bending strength** को दर्शाता है।

### Q.33 Rectangular और Circular sections का Moment of Inertia ($I$) और Section Modulus ($Z$) क्या होता है? *(ESE 2014)*
**उत्तर:** सर:
* **Rectangular ($b \times d$):** $I = \frac{bd^3}{12}$ और $Z = \frac{bd^2}{6}$
* **Circular (व्यास $D$):** $I = \frac{\pi D^4}{64}$ और $Z = \frac{\pi D^3}{32}$

### Q.34 Simply Supported Beam के मध्य में (a) Point Load $P$ और (b) पूरे span पर UDL $w$ के लिए अधिकतम Deflection कितना होता है? *(ESE 2014)*
**उत्तर:** सर:
* **केंद्र पर Point Load ($P$):** $\delta_{\max} = \frac{PL^3}{48EI}$ (और सिरों पर slope $\theta = \frac{PL^2}{16EI}$)।
* **पूरी लंबाई पर UDL ($w$):** $\delta_{\max} = \frac{5 wL^4}{384EI}$ (और सिरों पर slope $\theta = \frac{wL^3}{24EI}$)।

### Q.35 Cantilever Beam क्या होती है? *(ESE 2013)*
**उत्तर:** सर, वह बीम जिसका एक सिरा दीवार या कॉलम में **पूरी तरह जकड़ा (fixed)** हो और दूसरा सिरा हवा में **मुक्त (free)** हो (जैसे घर की बालकनी या छज्जा)। इसमें ऊपर से लोड पड़ने पर हमेशा **Hogging (negative) BM** आता है, इसलिए मुख्य सरिए ऊपर (top face) में डाले जाते हैं।

### Q.36 किसी संरचना की Elasticity से आप क्या समझते हैं? *(ESE 2013)*
**उत्तर:** सर, यह संरचना या सामग्री का वह गुण है जिसके कारण बाहरी लोड हटा लेने पर वह अपनी विकृत (deformed) अवस्था से **पूरी तरह अपने पुराने मूल आकार और स्थिति में वापस लौट** आती है।

### Q.37 Fatigue क्या होता है? *(ESE 2013)*
**उत्तर:** सर, जब किसी पुल, रेलवे ट्रैक या मशीन के हिस्से पर करोड़ों बार **बार-बार लगने वाले या बदलने वाले लोड्स (cyclic/repeated loading)** आते हैं, तो सामग्री अपनी सामान्य yield strength से भी काफी कम stress पर धीरे-धीरे सूक्ष्म दरारें फैलाकर अचानक **brittle तरीके से टूट** जाती है—इसी को **Fatigue Failure** कहते हैं।

### Q.38 Modulus of Elasticity ($E$) क्या होता है? *(ESE 2013, 2016)*
**उत्तर:** सर, Hooke's Law के अनुसार proportional limit के अंदर stress और strain का अनुपात हमेशा एक स्थिरांक होता है जिसे **Modulus of Elasticity ($E = \sigma/\epsilon$)** कहते हैं।

### Q.39 Keys और Couplings क्या होते हैं? *(ESE 2009)*
**उत्तर:** सर, **Key** धातु का एक छोटा टुकड़ा है जो घूमते हुए **शाफ्ट और पुली/गियर** को आपस में लॉक करता है ताकि पावर ट्रांसफर हो सके और फिसलन न हो। जबकि **Coupling** दो अलग-अलग शाफ्टों को सिरे से जोड़कर एक लंबा शाफ्ट बनाने के काम आता है।

### Q.40 बैलगाड़ी या ट्रेन के पहिए पर चढ़ाए जाने वाले लोहे के टायर (rim) का व्यास, पहिए के व्यास से थोड़ा कम क्यों रखा जाता है? *(ESE 2009)*
**उत्तर:** सर, इसे **Shrink Fitting** कहते हैं। टायर को पहिए पर चढ़ाने से पहले **गर्म** किया जाता है जिससे वह फैलकर बड़ा हो जाता है और आसानी से पहिए पर चढ़ जाता है; फिर ठंडा होने पर वह सिकुड़कर पहिए को बेहद मज़बूती से जकड़ लेता है ताकि चलते समय कभी बाहर न निकले।

### Q.41 Shear Centre जानना क्यों महत्वपूर्ण है? *(ESE 2009)*
**उत्तर:** सर, **Shear Centre** किसी क्रॉस-सेक्शन का वह बिंदु है जिससे होकर यदि बाहरी transverse shear force गुज़रे, तो बीम में केवल **शुद्ध Bending** होगी और कोई **मरोड़ (Torsion/Twisting)** नहीं आएगा। Channel (C-section) और Angle जैसे पतले असमित (unsymmetrical) सेक्शन torsion में बहुत कमज़ोर होते हैं, इसलिए लोड को हमेशा उनके Shear Centre से गुज़ारना ज़रूरी है।

### Q.42 Pre-strain (Lack of fit) को परिभाषित कीजिए। *(ESE 2008)*
**उत्तर:** सर, यदि किसी indeterminate truss या फ्रेम का कोई एक member निर्माण की गलती से थोड़ा छोटा या बड़ा बन जाए और उसे ज़बरदस्ती खींचकर या दबाकर फिट किया जाए, तो बिना किसी बाहरी लोड के भी पूरे ढांचे में जो तनाव व विकृति पैदा हो जाती है, उसे **Stress due to lack of fit** और उस strain को **Pre-strain** कहते हैं।

### Q.43 Mohr's Circle का क्या महत्व है? *(ESE 2008)*
**उत्तर:** सर, **Mohr's Circle** एक बेहद सरल और शक्तिशाली **graphical तरीका** है जिससे बिना लंबे त्रिकोणमितीय सूत्र लगाए किसी भी झुके हुए तल ($\theta$) पर Normal stress, Shear stress, Principal stresses और Maximum shear stress को तुरंत और साफ-साफ देखा व निकाला जा सकता है।

### Q.44 Engineers द्वारा Octahedral Shear Stress (Von-Mises) Theory को ज़्यादा पसंद क्यों किया जाता है? *(ESE 2008)*
**उत्तर:** सर, क्योंकि प्रयोगों (experiments) से सिद्ध हो चुका है कि **ductile metals (स्टील, एल्युमिनियम)** के लिए यह थ्योरी सबसे सटीक नतीजे देती है, यह pure shear और hydrostatic दोनों स्थितियों को सही से संभालती है, और इसका समीकरण गणितीय रूप से smooth व आसान है।

### Q.45 किसी बीम सेक्शन की bending strength किससे दर्शाई जाती है? *(ESE 2008)*
**उत्तर:** सर, **Section Modulus ($Z = \frac{I}{y_{\max}}$)** से। $Z$ का मान जितना ज़्यादा होगा, उस सेक्शन की Moment of Resistance ($M = \sigma \cdot Z$) उतनी ही ज़्यादा होगी।

### Q.46 Variable cross-section वाली बीम क्यों डिज़ाइन की जाती है? *(ESE 2008)*
**उत्तर:** सर, किसी लंबी बीम या पुल के गर्डर में Bending Moment पूरी लंबाई में बराबर नहीं रहता (कहीं ज़्यादा, कहीं कम)। यदि पूरी लंबाई में एक ही मोटाई रखेंगे तो जहाँ BM कम है वहाँ सामग्री बर्बाद होगी। इसलिए बड़े पुलों (जैसे संतुलित कैंटिलीवर ब्रिज) में BM के हिसाब से गहराई घटाते-बढ़ाते हैं (Beam of uniform strength) ताकि **वजन और लागत दोनों बचें**।

### Q.47 Torsion क्या होता है? *(ESE 2008, 2016)*
**उत्तर:** सर, जब किसी शाफ्ट या बीम पर उसकी लंबाई के अक्ष (longitudinal axis) के चारों ओर घुमाने वाला **Twisting Moment / Torque** लगता है जिससे वह मरोड़ खाती है, तो उसे **Torsion** कहते हैं (जैसे L-beam, curved beam या कार का drive shaft)।

### Q.48 Dilatation (Volumetric Strain) से आप क्या समझते हैं? *(ESE 2007)*
**उत्तर:** सर, किसी पिंड पर तीनों दिशाओं से बल लगने पर उसके आयतन में होने वाले परिवर्तन और मूल आयतन के अनुपात ($\epsilon_v = \frac{\Delta V}{V}$) को **Volumetric Strain या Dilatation** कहते हैं। यह तीनों लंबवत दिशाओं के strains के योग ($\epsilon_v = \epsilon_x + \epsilon_y + \epsilon_z$) के बराबर होता है।

### Q.49 Intermediate column कैसे फेल होता है? *(ESE 2007)*
**उत्तर:** सर, **Short column** केवल crushing से और **Long column** केवल buckling से फेल होता है; जबकि **Intermediate column** इन दोनों के **संयोजन (combination of crushing and buckling)** से फेल होता है (इसे Rankine या Johnson's parabolic formula से हल करते हैं)।

### Q.50 Steel में Carbon की मात्रा बढ़ाने से उसके Stress-Strain Curve पर क्या असर पड़ता है? *(ESE 2007, 2016)*
**उत्तर:** सर, Carbon बढ़ाने से स्टील की **Yield और Ultimate Strength तो ऊपर उठती है**, लेकिन उसका **Yield plateau छोटा होकर गायब** हो जाता है और कुल लंबाई में खिंचाव (ductility) बहुत घट जाता है—अर्थात् ग्राफ धीरे-धीरे **Brittle material** के ग्राफ जैसा होता जाता है।

### Q.51 Bend Test क्या होता है? *(ESE 2007)*
**उत्तर:** सर, यह साइट और लैब में सरियों (TMT bars) की **Ductility और Toughness** जांचने का एक सरल टेस्ट है। इसमें सरिए को एक तय व्यास के मैंड्रेल के चारों ओर **$180^\circ$ (या $90^\circ$)** पर मोड़ा जाता है—अगर मुड़ने के बाद बाहरी सतह पर **कोई दरार (crack) न आए**, तो सरिया पास माना जाता है।

### Q.52 Strength of Materials पढ़ने का मुख्य उद्देश्य क्या है? *(ESE 2006)*
**उत्तर:** सर, यह सुनिश्चित करना कि किसी भी लोड के संयोजन के तहत इस्तेमाल की गई सामग्री अधिकतम आंतरिक **stresses (ताकत)** और **deformations (deflection/serviceability)** दोनों के विरुद्ध सुरक्षित रहे।

### Q.53 Principle of Superposition क्या होता है? *(ESE 2006)*
**उत्तर:** सर, किसी **linearly elastic** संरचना पर यदि एक साथ कई लोड्स लग रहे हों, तो किसी बिंदु पर कुल stress, strain या deflection, हर एक लोड के कारण **अलग-अलग पैदा हुए stresses/deflections के बीजगणितीय योग (algebraic sum)** के बराबर होता है। *(ध्यान रहे: यह Strain Energy पर लागू नहीं होता!)*

### Q.54 Neutral Axis क्या होती है? *(ESE 2006)*
**उत्तर:** सर, जब कोई बीम मुड़ती है तो एक तरफ की परतें सिकुड़ती हैं और दूसरी तरफ की फैलती हैं—इन दोनों के बीच में एक ऐसी परत होती है जिसकी लंबाई में **कोई बदलाव नहीं** होता (**Neutral Layer**)। इस परत और बीम के क्रॉस-सेक्शन के कटान से बनने वाली रेखा को **Neutral Axis** कहते हैं—इस रेखा पर **Bending Stress हमेशा शून्य** होती है।

### Q.55 Conjugate Beam क्या होती है? *(ESE 2006)*
**उत्तर:** सर, यह असली बीम के बराबर लंबाई की एक **काल्पनिक (imaginary) बीम** होती है जिसके ऊपर असली बीम के **$M/EI$ diagram** को लोड के रूप में रखा जाता है। इस काल्पनिक बीम का **Shear Force** असली बीम का **Slope** देता है, और इसका **Bending Moment** असली बीम का **Deflection** देता है।

### Q.56 किसी Compression Member (Column) की ताकत किन मुख्य कारकों पर निर्भर करती है? *(ESE 2006)*
**उत्तर:** सर, मुख्य रूप से 4 कारकों पर: (1) **Area of cross-section**, (2) **Minimum Radius of Gyration ($r_{\min}$)**, (3) **Effective Length ($L_{\text{eff}}$ — लंबाई व end conditions)**, और (4) सामग्री की **Modulus of Elasticity ($E$) व Yield Strength**।

### Q.57 Mechanics of Materials (या Strength of Materials) से आप क्या समझते हैं? *(ESE 2005, 2014)*
**उत्तर:** सर, यह यांत्रिकी (Mechanics) की वह शाखा है जो किसी ठोस (deformable) पिंड पर लगाए गए **बाहरी बलों (external loads)** और उनके कारण पिंड के अंदर पैदा होने वाले **आंतरिक प्रभावों (internal stresses, strains और deformations)** के आपसी संबंध का अध्ययन करती है।