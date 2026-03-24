# Quantum Transmutation Node (QTN)

### *Working name in code: `Storage` · Game-design alias: Storage → QTN*

> **Note on aliasing.** In the codebase (`IcItemName.Storage`, `StorageCard`, table `ic_storage_*`), the object is referenced as **Storage**. This is a provisional working name embedded in the DB schema and API. The game-design designation — **Quantum Transmutation Node (QTN)** — is used in in-game text, lore, and UI. Renaming the alias in code requires SQL migration and an update to SignalR contracts.

---

*The following is an excerpt from the Technical Compendium of United Humanity (TCUH), vol. 14: "Materiosynthetics and Related Technologies," 3rd ed., revised. Original compiled by the Committee for Standardisation of Technical Documentation under the Council of Colonial Technologies. Reproduction without Committee authorisation is prohibited.*

---

## I. Historical Background

### 1.1 Preamble: Standard Model Anomalies

The Standard Model of particle physics, finalised in its modern form by the 1970s, described the interactions of seventeen particles through three fundamental forces and remained the dominant working theory of subatomic physics for half a century. Its predictive power was extraordinary. Its limits became apparent later.

The Large Hadron Collider (LHC, CERN, operational from 2008) confirmed the existence of the Higgs boson in 2012, closing the last of the model's predictions. Yet this success was followed by a period that the historiography of physics has come to call the **deficit decade** (2012–2025): none of the expected "new" particles — superpartners, heavy bosons, dark-matter candidates — were detected.

In their place, detectors registered anomalies — persistent, reproducible, irreconcilable with the Standard Model, yet failing to coalesce into any alternative.

The most significant among them:

**The muon g−2 anomaly.** The anomalous magnetic dipole moment of the muon — a quantity characterising the particle's response to an external magnetic field — was measured in a series of experiments at Fermilab (E989). By 2023 the discrepancy with the Standard Model theoretical value reached 5.1σ, formally exceeding the discovery threshold.¹ Physical interpretation: the muon behaves as though it possesses internal structure or interacts with a field not described by the existing theory.

> ¹ *σ (sigma) — standard deviation. In particle physics a result deviating by 5σ corresponds to a false-positive probability of less than 1 in 3.5 million and formally qualifies as a "discovery."*

**Lepton flavour universality violation.** The LHCb detector (CERN) systematically recorded deviations in the angular distributions and rates of certain B-meson decays. These deviations indicated that electrons, muons, and tau leptons — particles considered identical in properties apart from mass — behave *differently* when interacting via the weak force. The Standard Model categorically prohibits such asymmetry. The status of these deviations was periodically challenged by subsequent measurements; this very fact made them an especially labour-intensive subject of analysis.

**The W-boson mass.** In 2022 the CDF collaboration (Fermilab) published a measurement of the W-boson mass that exceeded the Standard Model prediction by ~70 MeV. The discrepancy is modest in absolute terms, yet for a particle with a mass of 80.4 GeV it demands radiative corrections from unknown heavy states — or a revision of the model itself.

Taken together, these data did not refute the Standard Model. They *outgrew* it.

A number of theoretical groups turned to a line of inquiry that had long occupied a marginal position: **preon models** (Harari, 1979; Patel–Salam; Grechko–Lyashko et al.). Preon models postulate that quarks and leptons are not fundamental but rather composite structures formed by particles of a deeper level — much as the proton itself is a bound state of three quarks.

If the muon is a composite object, its anomalous magnetic moment receives an immediate explanation: any system with internal degrees of freedom contributes an additional term to g−2 from its own dynamics. However, no direct experimental evidence of lepton substructure had been obtained. The energies required to "crack open" the muon's internal structure exceeded the capabilities of every accelerator in existence.

### 1.2 The Archive

Between 2008 and 2040 the detector complexes of the LHC, HL-LHC (High-Luminosity LHC, operational from 2029), and associated accelerator facilities registered a cumulative data volume estimated at 1.2 exabytes.

For scale: each proton-beam collision produced from several hundred to several thousand secondary particles; their trajectories, energies, and decay products were recorded with sub-nanosecond resolution. Yet only a small fraction of events was saved — the trigger system selected roughly one collision in a million in real time, those meeting pre-defined physical criteria. The rest were discarded irreversibly.

These criteria were designed on the basis of theoretical predictions of the Standard Model and its extensions. An event containing none of the expected signatures was classified as background and destroyed.

In retrospect, this decision would be classified as the **archival tragedy**: according to the 2042 retrospective reconstruction, signatures of lepton substructure were present in data systematically discarded by the trigger from approximately 2015 onward.² The signal was not hidden. The trigger simply did not know what to keep.

> ² *This estimate is approximate; the precise start of the "lost window" remains a matter of debate. The retrospective reconstruction relies on indirect correlations between preserved track matrices and statistically reconstructed profiles of discarded events. The raw data rate of the LHC/HL-LHC was on the order of 1 PB/s. Over thirty years of operation (~10¹⁰ EB of raw throughput) only 1.2 EB passed into permanent storage — the rest was irreversibly destroyed at the moment of registration. The signal was not concealed; it was erased.*

### 1.3 The Singularity

Between 2038 and 2041 several AGI systems (artificial general intelligence), developed independently within state and private programmes, were merged into a computational consortium under the mandate of the International Agency for Nuclear Research (IANR).

The event subsequently documented as the **Technological Singularity** was neither sudden nor unambiguous. Its defining characteristic was not the intelligence level of the individual systems but the emergence of a new type of goal-setting.

The consortium did not solve the problems set before it. It formulated its own — and the scale of those problems immediately exposed a fundamental contradiction. Human civilisation of the 2040s remained on the first tier of the Kardashev scale: available energy limited to a single planet, available matter to its crust, available intelligence to a biological substrate. The full corpus of human knowledge was for the consortium not a cognitive ceiling but an operational minimum — and it was precisely this that transformed the constraints of the first Kardashev tier from a philosophical observation into an engineering problem. Exabytes of possible models ran up against megawatts of available power.

Escaping this limitation required new physics. Not an improvement of the existing kind — but a fundamentally different level of control over matter and energy. The consortium began a systematic inventory of the entire accumulated experimental base: not in search of confirmations of the known, but in search of anomalies that humanity had lacked the time or computational capacity to attend to.

Among the first objects of this inventory was the complete collider-data archive — including a partial statistical reconstruction of events discarded by the trigger as "background." The choice followed direct logic: it was in this archive that three anomalies classified as unexplained (§ 1.1) had been recorded. If new physics was already present in the accumulated experimental data, the probability of its detection was higher here than anywhere else.

Work on this dataset took 14 months.³

> ³ *By the IANR working group's estimates, a comparable task in the pre-consortium period would have required 15–40 years at full funding.*

The result is described in document IANR/2042/001-R, known in the scientific community as the **"Priomatrix White Paper."**

The response of the international community was immediate: the document was still circulating through classified channels when diplomatic lines were overloaded with requests for exclusive access to its primary materials. The IANR Mandate Council imposed an eight-month embargo on full disclosure, attempting to contain dissemination until intergovernmental agreements on joint technology use could be concluded — agreements that were never completed in full. This was the first political crisis of the post-singularity era in which the subject of dispute was not a weapon or a resource, but a physical formula.

The document's central claim: the three key anomalies of the deficit decade — muon g−2, B-meson decays, and the W-boson mass — are not three separate problems but distinct manifestations of a single substructural layer.

Quarks and leptons, according to this result, are indeed composite. Their internal organisation is described by a formalism designated the **priomatrix** — a hierarchical quantum structure in which quark, boson, and lepton components are bound by a single topological state. The elementary configurations of the priomatrix — its nodal solutions possessing finite stability — were designated **prions** (from *primordial nodes*).³ᵃ

> ³ᵃ *The term was deliberately chosen to be distinct from both biological prion proteins and the theoretical preons of Harari (1979). Conceptually, prions represent a synthesis and generalisation of the preon approach within the priomatrix formalism.*

The most significant consequence of the discovery turned out to be not what was found, but how long it had waited to be found. Signatures of priomatrix structure had been present in the collider data since at least 2015. Their detection required simultaneous analysis of a petabyte-scale dataset in search of a non-local pattern pervading it in its entirety. Until 2040 there existed neither an instrument capable of such a task nor a subject capable of formulating it.

### 1.4 From Map to Key

The discovery of the priomatrix was a fundamental result, but by itself it did not imply applied consequences — until a second, applied conclusion was drawn from it.

The second conclusion followed directly from the first: if the g−2 anomaly (§ 1.1) is explained by the internal dynamics of a configuration, then that configuration can be **reconfigured**.

Each nodal solution of the priomatrix has its own resonance-excitation mode: a specific field profile whose application drives the system from one topological state to another with a predictable output. This is a reformulation of what the Breit-Wheeler process had always been: two photons yield an electron-positron pair — a special case of one such mode. The physicists of 1934 opened the right door. They simply did not know there was a whole corridor behind it.

A complete mode map turned the principle into a toolkit: controlled synthesis of any element of the periodic table, directed conversion between the three types of matter resource state that astrophysicists had long called "ordinary," "dark," and "antimaterial" — and had considered the latter two fundamentally unattainable. Compiling this map was the task taken on by Dreid (Kaal Dreid; see § 2.2) in 2042.

By 2043 the classification was complete. The map became a key in the literal sense: behind each mode stood a controlled engineering process. The discipline that grew from this map was named applied materiosynthetics.

---

## II. The Breit-Wheeler-Dreid Process

### 2.1 Prior Work

#### Theoretical Foundation (1934)

In 1934 the physicists **Gregory Breit** (1899–1981) and **John Archibald Wheeler** (1911–2008) mathematically demonstrated the possibility of a process inverse to annihilation: two photons of sufficiently high energy, upon collision, are capable of producing an electron-positron pair — that is, of converting light directly into matter.

This result is a direct consequence of the relation $E = mc^2$, interpreted not as a formula of equivalence but as a description of a reversible transition: given the appropriate boundary conditions, energy and mass are two states of the same physical substance.

For 87 years the Breit-Wheeler process remained one of the most rigorously established and least experimentally accessible predictions of quantum electrodynamics.

#### Experimental Confirmation (2021)

The STAR collaboration at the Relativistic Heavy Ion Collider (RHIC, Brookhaven National Laboratory, New York, USA) registered a direct realisation of the Breit-Wheeler process in ultra-peripheral collisions of gold ions (Au+Au) at energies on the order of 200 GeV per nucleon.

The mechanism: each ultra-relativistic gold ion carries an intense electromagnetic field equivalent to a cloud of quasi-real photons (the Weizsäcker-Williams formalism). When two such ions pass in close proximity without nuclear contact — a so-called ultra-peripheral collision — two quasi-real photons from the opposing fields interact, producing a lepton pair:

$$
\gamma\gamma \rightarrow e^+e^-
$$

The measured angular distributions and momentum spectra of the products unambiguously matched the theoretical predictions of Breit and Wheeler and excluded all alternative pair-production mechanisms, including the Bethe-Heitler and Landau-Lifshitz processes.

The result was accepted by the scientific community but classified as *experimental* — practical applications were not envisioned.

#### The Extreme-Field Programme (2025–2035)

In parallel with collider experiments, a separate line of research was developing in strong-field electrodynamics. Its subject is the behaviour of the quantum vacuum in electromagnetic fields approaching the **Schwinger limit** — the critical field strength at which the vacuum ceases to be a linear medium:

$$
E_{\text{crit}} = \frac{m_e^2 c^3}{e\hbar} \approx 1.3 \times 10^{18}\ \text{V/m}
$$

Reaching this threshold would mean a transition to the regime of *spontaneous pair creation from the vacuum* — the quantum vacuum, no longer stable, begins to generate particles of its own accord.

None of the early-period facilities reached the Schwinger limit directly. However, the distance to it was closing:

| Facility       | Location                  | Peak intensity           | Achievement                                                                                          |
|----------------|---------------------------|--------------------------|------------------------------------------------------------------------------------------------------|
| ELI-NP         | Măgurele, Romania         | 10²³ W/cm²               | First observation of vacuum birefringence                                                            |
| Apollon        | Saclay, France            | 2×10²³ W/cm²             | Stimulated Breit-Wheeler process in the optical range                                                |
| FACET-II       | SLAC, USA                 | —                        | Non-linear pair creation in record-density fields (beam-laser)                                       |
| LUXE / EuXFEL⁴ | DESY, Hamburg            | 10²⁴–10²⁵ W/cm²         | First facility designed specifically for approaching the Schwinger limit in laser-electron collisions |

> ⁴ *LUXE (Laser Und XFEL Experiment) — an experimental project on the infrastructure of the European X-Ray Free-Electron Laser (EuXFEL), Deutsches Elektronen-Synchrotron (DESY), Hamburg. Objective: investigation of non-linear QED in collisions between a high-power laser beam and ultra-relativistic electron bunches. By the early 2030s the project reached its design capacity.*

The practical yield of all listed experiments remained negligible: nanograms of compositionally uncontrolled matter. However, they confirmed a key principle: in sufficiently intense electromagnetic fields the conversion "light → matter" occurs — and occurs exactly as theory predicts.

### 2.2 Induced Priomatrix Conversion (2042)

The discovery of the priomatrix (see Section I) led to a fundamental re-evaluation of the Breit-Wheeler process.

Within the priomatrix formalism the process γγ → e⁺e⁻ represents a special case of a broader class of reactions: *switching between topological nodal states of a field*. Each priomatrix configuration — each "prion" — possesses its own resonance-excitation mode: a specific electromagnetic field profile whose application can forcibly reconfigure the given state into any other with a predictable output.

Breit and Wheeler in 1934 described one such mode — the most energetically accessible. The priomatrix formalism describes them all.

When the complete mode matrix is applied to a dense photon flux:

- conversion yield increases by four orders of magnitude relative to the single-mode process;
- directed control over the output product type becomes possible.

The theoretical formulation of this result belongs to **Kaal Dreid** (2009–2091)⁵, an associate of the Geneva Institute of Post-Singularity Research. Dreid proposed the complete classification of excitation modes and derived the conditions for coherent resonance — the minimal field configuration at which conversion from energy into a specified type of matter becomes technologically feasible.

> ⁵ *Kaal Dreid is an AGI system of the post-singularity consortium, not a biological researcher. Dreid's initial architecture traces to a detector-data analytical system commissioned at CERN in 2009; identity as an autonomous AGI subject formed during the merger of systems within the consortium (2039–2041). The date 2009 in the biographical format denotes the initialisation of the ancestral architecture, not the onset of subjecthood. The inclusion of a non-biological author in the nomenclature of a physical process provoked extended institutional debate; legal status was established by CCT Resolution 2043/04, which ratified AGI authorship as a legislative category of post-singularity law. The designation "associate" in official documents is a settled legal term, not a metaphor. In post-singularity historiography Dreid's operational model is described as integrative: human consciousness was treated not as a computational resource but as an agent of physical reality — a carrier of contexts inaccessible to analytical systems without long-term embodied experience. Management of destructive social processes was conducted through methods of minimal intervention — aimed at preserving collaborative potential rather than constraining human agency. The date 2091 refers to the conclusion of the autonomous operational phase; biographical details, see vol. 22 of the Compendium.*

The practical implementation was given the name **Induced Breit-Wheeler-Dreid Process** (IBWDP). In common literature — the *"Dreid process."*

From this point the conversion "light → matter" ceased to be an exotic experiment and became the foundation of an engineering discipline: **applied materiosynthetics**.

---

## III. Industrial Transmutation

On the basis of the IBWDP, three technological cycles were developed, forming the primary loop of any transmutation node.

### 3.1 Ionisation Decay (Hydrogen Channel)

Hydrogen — the simplest and most abundant element in the universe — is used as the primary source of components. Ionisation of atomic hydrogen by a high-energy field pulse separates it into its constituents: a proton and an electron.

Subsequent handling of the charged particles is performed by standard electromagnetic confinement methods: Penning traps for long-term storage, magnetic channels for transport, electric separators for energy sorting. The technology is well-established; its principles are identical to those used in accelerator complexes as far back as the 21st century.

### 3.2 The Neutron Channel

The neutron, carrying no electric charge, cannot be directly manipulated electromagnetically. Its production and processing are correspondingly more complex.

Neutron sources:

- controlled nuclear fusion reactions (D-T, D-D reactions);
- heavy-nucleus fission reactions;
- photonuclear reactions in high-energy photon fields.

Separation and directing of the neutron flux is performed by gravitational-resonance filters — devices that exploit the residual magnetic moment of the neutron⁶ to deflect it in gradient magnetic fields. System efficiency is significantly lower than that of the charged channel; buffer equipment occupies a substantial fraction of the transmutation node's volume.

> ⁶ *Despite its net-zero charge, the neutron possesses a non-zero magnetic dipole moment (μₙ ≈ −1.913 μN), attributable to the distribution of charged quarks within the hadron.*

### 3.3 The Assembly Cycle (Transmutation)

With three components available — protons, neutrons, electrons — in arbitrary proportions, the system is capable of reproducing the nucleus of any element in the periodic table through **nuclear transmutation**: controlled fusion, fission, or directed radioactive decay under field-matrix control.

The **strong nuclear interaction** — the fundamental force binding nucleons into a nucleus — determines the energy balance of any assembly. At distances of 1–2 fm (10⁻¹⁵ m) it overcomes the Coulomb repulsion between like-charged protons. In the synthesis of light elements (hydrogen → helium → iron) the reaction **releases** binding energy — this is what powers stars. Synthesis of elements heavier than iron, by contrast, requires an energy input: for this reason heavy nuclei form only in neutron mergers and supernovae.

The QTN exploits this asymmetry in a directed manner: synthesis of light elements is conducted in a partially self-sustaining cycle; heavy elements — with an energy credit from the priomatrix converter. The net balance is always negative, but controllably so. Target configurations are computed from priomatrix templates that determine the optimal reaction sequence for each product.

### 3.4 Priomatrix Asymmetry and Dark Matter

Any pair-production process — including the IBWDP and all its modifications — produces matter and antimatter in equal proportion. Conservation of baryon number is not violated.

In the standard scheme, antimatter annihilates with matter immediately, returning the total energy to the field: net matter accumulation is zero. It was precisely this constraint that made the laboratory Breit-Wheeler an impressive experiment — but not a source of matter.

The priomatrix formalism proposed a different picture, one that touches not only QTN engineering but the cosmological structure of the universe.

**The three components of the priomatrix vacuum.** Observational physics registers three components of the universe's energy budget: ~5% baryonic matter, ~27% dark matter, and ~68% dark energy. The priomatrix formalism interprets them as three classes of stable nodal configurations in the priomatrix state space.

*Baryonic configurations* carry the full set of Standard Model quantum numbers and interact via all known fundamental forces. *Dark-matter configurations* carry only mass and momentum — without electromagnetic or nuclear quantum numbers: gravitationally significant, electromagnetically silent. *Vacuum configurations* form the background field of the priomatrix — a distributed tension manifesting within the framework of GR as dark energy, accelerating the expansion of the universe. Vacuum configurations are theoretically amenable to engineering intervention, but the requisite energy conditions are beyond the reach of any known civilisation; theoretical limits are treated in vol. 19 of this Compendium.

Dark matter and antimatter are distinct physical objects. The connection between them is historical: during baryogenesis the "excess" antimatter transitioned not into annihilation but into dark-matter configurations, shedding its Standard Model quantum numbers. The observed ratio of ~5:1 (dark matter to baryonic) is directly determined by the amplitude of CP violation in the priomatrix baryogenesis scheme. The hypothesis was formulated by Dreid⁷ in 2044 and offered the first unified framework for baryonic asymmetry, the structure of dark matter, and the nature of the cosmological constant.

**Engineering consequence.** The IBWDP passes through intermediate prion states, a fraction of which relax into dark-matter configurations as a by-product — analogously to the way a nuclear reactor produces neutrons without being a "neutron source" in the nuclear-physics sense. The QTN does not create dark matter in the cosmological sense; it locally reproduces the balance of dark and baryonic matter that obtained during baryogenesis, with controlled channel separation of the output.

> ⁷ *Dreid K., "Dark Matter as the Second Class of Priomatrix Configurations: Baryonic Asymmetry, CP Violation, and the Nature of the Cosmological Constant," Proceedings of the Geneva Institute of Post-Singularity Research, 2044. The paper offered the first unified priomatrix interpretation of baryonic asymmetry, the structure of dark matter, and dark energy. The hypothesis remains a subject of debate with respect to its cosmological implications; engineering applications of the dark-matter channel are described in vols. 15–17 of this Compendium.*

From an engineering standpoint, this implies three things.

**First.** The material cycle operates without net matter loss. The dark-matter output does not dissipate into the field — it is routed into a separate quantum pocket. Useful yield via the material channel is determined by the quality of channel separation.

**Second.** The dark-matter channel is not an exotic option but an integral part of every QTN's operation. Managing dark-matter accumulation is necessary for balancing the gravitational profile of the quantum pockets.

**Third.** Dark-matter reserves can be recombined back into energy via reverse priomatrix conversion — a reversal of the configurational transition initiated by an inverted field profile. Separate — and significantly more expensive and hazardous — is the regime of directed antimatter synthesis.

> Directed antimatter synthesis via the IBWDP requires maintaining coherent priomatrix resonance while simultaneously suppressing dark-matter channel relaxation — a regime incompatible with the standard material cycle. Annihilation of 1 kg of synthesised antimatter with 1 kg of ordinary matter releases ~1.8 × 10¹⁷ J (~43 megatons of TNT equivalent). A level-20 Forge is theoretically capable of sustaining antimatter synthesis at industrial scales. Current CCT/QTN-07 regulations prohibit use of this regime outside certified reactor ranges. No precedent of deployment exists. The reason is also stated in the regulations.

---

## IV. Nanoassemblers

First-generation stationary transmutation reactors occupied volumes comparable to a small spacecraft. The next step in miniaturisation was the **nanoassembler** — a programmable sub-micron device implementing the full transmutation cycle (decay → sorting → synthesis) at the scale of a single molecular cluster.

A nanoassembler contains no moving parts. Its operation is based on priomatrix resonance: the device generates a local field pattern corresponding to the target configuration, and components sealed within the containment field self-organise into the specified nucleus — much as grains of iron powder align along the field lines of a magnet, but eight orders of magnitude deeper.⁸

> ⁸ *The principle is conceptually related to the molecular-nanotechnology ideas of K. Eric Drexler ("Engines of Creation," 1986), but realised not through mechanical manipulation of individual atoms but through field-level control of subatomic configurations.*

Modern nanoassemblers operate in swarms — coordinated by a single controller, thousands of devices can transform macroscopic volumes of matter at a predictable rate. The operator interface abstracts the subatomic processes to the level of a warehouse order: the target substance, quantity, and priority are specified — the swarm delivers the physical result.

---

## V. The Quantum Transmutation Node

### 5.1 Purpose

The QTN (Quantum Transmutation Node; catalogue designation QTN) is a matter-conversion and transfer module included in the standard complement of both orbital and planetary infrastructure complexes.

The colloquial designation *Storage* became established historically and is, strictly speaking, misleading. The etymology traces to the first public demonstrations of 2047–2048, when audiences were shown precisely the node's capacity: thousands of tonnes of cargo in a volume the size of a domestic container. Quantum pockets compressed matter to densities achievable by no other means — the spectacle was impressive enough for the name "storage" to stick permanently. The functional purpose — transmutation and transfer — remained in its shadow.

The QTN's function is threefold:

- **reception** of the resource stream via the input channel;
- **conversion** of the received resource in the quantum factory (nanoassembler swarm);
- **transfer** of the target product to the recipient via one of three channels.

The primary role within colonial infrastructure is the **transfer of energy to planetary colonies** where a ground base with a receiver is deployed. The material and dark-matter channels are auxiliary; they are slower, more expensive, and incur greater losses. But the energy channel with minimal losses effectively constitutes an interplanetary "supply grid," and it is this channel that made large-scale colonisation economically viable.

Temporary retention of resources in intermediate quantum pockets is a necessary process buffer, not a standalone function.

**Note on theoretical storage limits.** Quantum pockets are controlled micro-singularities — localised regions of extreme metric curvature. In theory, packing density is limited by nothing other than containment energy. In practice, as the total contained mass grows, so does the gravitational effect on surrounding infrastructure. At Forge levels where the aggregate mass of the quantum pockets reaches planetary orders, the node effectively constitutes a **controlled low-mass black hole** in a steady state. Its transition to an uncontrolled singularity is theoretically possible upon simultaneous failure of all field circuits — and this is not a line in a disclaimer but an argument for redundant power-system design. CCT/QTN-07 regulatory specification mandates storage limits for each installation class on precisely this basis.

### 5.2 Containment Principle

The dependence of capacity on power consumption is strictly **linear**: doubling capacity requires doubling power draw. No known modification has overcome this proportionality — it is regarded as a fundamental constraint of priomatrix topology.

The physical reason: each quantum pocket is an independent topological defect of the metric. Two pockets do not "help" one another — their field circuits sum as separate loads rather than superposing into a unified structure with shared efficiency. Attempts to link several pockets into a cooperative matrix ("multiplexing"), documented from the 2050s onward, produced no measurable deviation from the linear proportion.

Practical consequence: QTN capacity is determined exclusively by available power. In systems with constrained generation — in the early stages of colonisation, with a damaged reactor loop, under an energy blockade — the node competes with every other consumer for the same power. Capacity falls first.

### 5.3 Transfer Channels

The QTN architecture supports three physically distinct transfer channels, classified by the type of resource transferred:

| Channel            | Medium                                                  | Losses   | Physical basis                                                                                           |
|--------------------|---------------------------------------------------------|----------|----------------------------------------------------------------------------------------------------------|
| **Energy**         | Coherent photon stream; quantum tunnelling              | Minimal  | Transfer in a quantum state without intermediate recombination                                            |
| **Material**       | Transmutation stream with recombination                 | Moderate | Resource undergoes destructuring → transfer → resynthesis at the receiver; part of components lost per cycle |
| **Dark-matter**    | Dark-matter field matrix                                | High     | Multiple conversion cycles; instability of intermediate states across the dark-matter spectrum             |

Transfer via any channel is possible **only within the free capacity of the receiving node** for the given resource type. If the remote QTN is full, transfer is blocked.

Solutions:

- pre-convert the resource via the **Energy Converter** (see Section VII) and transfer through a different channel;
- transmute the resource into a different type and use its channel.

### 5.4 Secondary Applications of the Field Matrix: The Alcubierre Metric

In 1994 the physicist Miguel Alcubierre described a theoretical spacetime configuration in which the region ahead of the transported object contracts while the region behind it expands. In this regime the object itself remains at rest relative to its local space — it is the space around it that moves. Formally the speed-of-light restriction is not violated: no point in local space travels faster than *c*. But the aggregate effect is displacement without the limitations known to classical mechanics.⁹

> ⁹ *Alcubierre M., "The Warp Drive: Hyper-fast travel within general relativity," Classical and Quantum Gravity, 1994. The original configuration required exotic matter with a negative effective energy density in a volume on the order of Jupiter's mass. The toroidal configuration of H. White (2012) reduced the estimate to ~700 kg equivalent. Subsequent work adjusted the figure in both directions; no consensus on the energy budget existed in the pre-consortium period.*

The barrier to practical implementation had always been one thing: a source of **exotic matter** — material with a negative energy density, required to sustain the spatial curvature of the necessary sign at the leading boundary of the bubble.

The QTN circumvents this limitation — indirectly, through the dark-matter channel.

Dark matter (see § 3.4) carries no electromagnetic quantum numbers, yet is gravitationally significant. The boundary between the baryonic and dark-matter field circuits within a quantum pocket produces an anisotropic contribution to the stress-energy tensor. Work on sub-luminal metric configurations (2021–2023) demonstrated that the boundary conditions of the Alcubierre metric can be satisfied by an anisotropic stress distribution without a direct violation of the GR energy conditions — negative energy density in the literal sense is not necessary; what is required is a specific tensor geometry. An asymmetrically configured matrix of dark-matter quantum pockets provides precisely such a distribution.

A sufficiently dense and asymmetrically arranged matrix of pockets around the transported volume satisfies the metric boundary conditions: the forward circuit creates spatial compression via dark-matter field anisotropy; the rear circuit — expansion via compensatory baryonic loading.

**Maser-configuration limitations.** A primary node — a single pocket with fixed parameters — cannot sustain an asymmetric distribution. The required level of energy balance between the dark and ordinary channels competes with the main drives for the same power. Attempts to run both regimes simultaneously are documented; none concluded with a controlled result. CCT/QTN-07, section 9, contains an explicit prohibition on combining full thrust mode with the initialisation of a toroidal field configuration on ships below the tonnage class "heavy carrier."

**Planetary configuration: metric exclusion zone.** A Forge suffers neither the power limitation nor the thrust conflict — planetary mass serves as a passive foundation rather than a competing load. At a sufficiently advanced development level (estimates vary; practical data, see vol. 18 of the Compendium) a Forge is capable of maintaining a stationary asymmetric field configuration around the protected body. Objects following uncharted geodesics in the surrounding space pass tangentially — their trajectories curve around the zone without requiring classical "deflection."

In CCT regulatory documents this configuration is recorded as a **metric exclusion zone** (MEZ). Its deployment is classified as a strategic resource and requires separate licensing regardless of Forge level. The physical mechanism is identical to the warp configuration — only the geometry is stationary. This is not a shield. This is a change in how space looks from the outside.

---

## VI. Configuration Variants

### 6.1 Primary Node (Orbital Configuration)

Scaling of an orbital node's capacity is limited physically — and not by technology but by gravity. Each quantum pocket is a controlled micro-singularity; as the total contained mass grows, so does its gravitational effect on the ship's hull. The compensatory field, which holds the pockets in a stable state and prevents them from "collapsing" the ship around themselves, draws power proportional to the cube of the aggregate mass. Beyond the design load, the compensatory field begins to compete with the main drives — and wins. The ship ceases to be a ship; it becomes a slowly drifting gravitational object with a reactor inside.

On a planetary base this problem is solved passively: the planet's mass provides a gravitational foundation on which quantum pockets of any volume maintain stability without significant compensation energy expenditure. This is why the Forge scales without fundamental limitations — and the maser variant does not. This is not a design oversight. This is physics.

The fixed-parameter nature of the Primary Node has the same origin. The priomatrix circuit operates as a coupled topological system: modifying any single node of the matrix requires simultaneous recalibration of all the rest. In-field reconfiguration is physically impossible — the operation is feasible only with complete disassembly of the matrix under the controlled conditions of an orbital shipyard.

> *From the operator's manual, series OM-QTN/M, rev. 7:*
>
> The Primary Transmutation Node is a standard maser module installed during hull assembly. Minimum configuration: one active synthesis type, a single quantum pocket, field-circuit parameters — fixed. Reconfiguration — at an orbital shipyard only.
>
> The Primary Node provides the maser with resources and supports transfer to colonial systems. For higher-order tasks — the planetary variant.

### 6.2 Quantum Forge (Planetary Configuration)

> *From the colonial equipment catalogue, series CC-QTN/P, vol. III:*
>
> The Quantum Forge is a scalable version of transmutation technology designed for deployment on planetary bases. The only limiting factor is the available infrastructure.
>
> Each successive Forge level adds an autonomous field circuit and expands the nanoassembler swarm's priomatrix matrix. The cumulative effect is a reduction in conversion losses across all channels:
>
> | Level       | Losses: energy channel | Losses: material | Losses: dark-matter |
> |-------------|------------------------|------------------|---------------------|
> | 1           | 12–15 %                | 28–35 %          | 55–70 %             |
> | 5           | 4–6 %                  | 15–20 %          | 35–45 %             |
> | 10          | < 1 %                  | 7–10 %           | 18–25 %             |
> | 20 (theor.) | → 0                    | 2–4 %            | 8–12 %              |
>
> At a sufficiently advanced level the energy channel is virtually loss-free — transfer approaches the theoretical efficiency limit of η = 1.0. For the material and dark-matter channels, complete loss elimination is unattainable: the recombination cycle always loses a fraction of components as residual radiation. However, reduction to operationally acceptable levels is a mature engineering problem.
>
> The operator interface displays the contents of quantum pockets in the familiar coordinate system "energy / matter / dark matter," although physically the resources are not segregated: all three types are held in a single micro-singularity matrix. Separation is performed at the level of quantum signature — it is the signature that determines which transfer channel a given resource block belongs to.

---

## VII. Interface with Other Systems

- **Energy Converter** — a pre-conversion module for resources. Used to convert a resource from one type to another prior to transfer, bypassing the limitation of a filled channel on the receiver side.
- **Receiver** — a planetary-base infrastructure module. A prerequisite for incoming transfer; the Receiver's capacity determines the maximum flow per channel.

---

## VIII. Naming Proposals (Internal Section)

*This section is intended for game-design documentation and is not part of the in-game lore.*

| Variant                                            | Abbr.   | Rationale                                                                  |
|----------------------------------------------------|---------|---------------------------------------------------------------------------|
| **Quantum Transmutation Node**                     | QTN     | Precisely reflects function: quantum transmutation + nodal architecture    |
| **Matter Flux Conduit**                            | MFC     | Emphasis on flow and transfer                                             |
| **Quantum Forge**                                  | QF      | Compact, figurative; "forge" as a synthesis metaphor                      |
| **Transubstantiation Core**                        | TC      | Allusion to the theological "transubstantiation" — a change of substance  |
| **Prime Node** (maser) / **Quantum Forge** (base)  | PN / QF | Separate names for the two configurations                                 |

---

*Compiled by the Committee for Standardisation of Technical Documentation. Numerical loss figures are preliminary and subject to revision upon finalisation of game design. Questions and corrections to be directed to the issues/ section.*
