# Autonomous Authority in Space: Risk Tradeoffs and the Law of Delegation

**Letao (Theodore) Ouyang**\* · December 2024; revised November 2026

\* I am grateful to Professor Jonathan B. Wiener for his instruction, review, and feedback on this paper. I also thank Professor Mark Borsuk, my academic advisor at Duke, for his guidance. Discussions with Professors Wiener and Borsuk about the risk-risk framework helped shape my thinking. Any errors are my own.

## Abstract

Autonomous space systems require legal rules allocating authority among states, operators, and reviewers. Waiting for a command may expose a spacecraft to avoidable loss; delegating the command may allow its operator to impose risks on others. This Article argues that supervision should distinguish lawful authority to undertake an activity from evidence justifying autonomous execution. It proposes a two-threshold decision procedure and a task-specific authorization record that implement this distinction. The two thresholds and the timing test restate, for autonomous systems, what the law of delegation already asks of human delegates. States should authorize defined classes of action, require renewed justification when material assumptions change, and reserve individual approval for decisions where review remains effective or separate legal permission is required. The argument compares delayed spacecraft operations with orbital collision avoidance. Debris capture exposes the limits imposed by ownership and registry-state interests, while SETI shows why scientific verification cannot simply borrow spacecraft licensing powers. The space treaties supply responsibility, supervision, liability, and due-regard obligations without prescribing an algorithmic control architecture. Risk-risk analysis requires assessment of the proposed controls as well as the systems they constrain. Advance authorization is defensible only where its factual basis can be examined, its external effects justified, and its exercise reconstructed after a consequential event.

## I. Introduction

A spacecraft may need to act before its operators can approve a command. A satellite may avoid one collision by moving into a trajectory that changes another operator's risk. A radio telescope may detect an unusual signal with no evidence that the signal is extraterrestrial. The decisions differ in the interests they affect and the institutions competent to govern them. A regulator deciding whether to permit a maneuver policy faces a legal problem that scientific investigators assessing a possible technosignature do not. As Part III shows, existing law governs the actors in space activities but leaves operational choices open.

This Article argues that autonomy should be regulated by allocating decision rights at identifiable stages of an activity. The relevant distinction is between actions already justified within an authorized operating range and decisions that alter that range, the mission's purpose, or third-party exposure beyond that assessed and authorized. An operator should sometimes be permitted to execute a validated action without contemporaneous human approval. That permission should be accompanied by advance justification, conditions that terminate or narrow it, and evidence enabling another institution to examine its use. Conversely, a useful prediction does not itself authorize a maneuver, a successful approach does not authorize capture of another state's object, and an anomalous signal does not authorize a claim of confirmed extraterrestrial intelligence.

This Article contributes a two-threshold decision procedure. The first threshold asks whether the actor has authority to undertake the activity and impose the relevant exposure; the second asks whether the evidence justifies delegating it. Where both are met, the procedure turns to the time at which human review can still change the outcome, and it treats individual approval, advance-constrained action, and fallback behavior as separate supervisory choices. The Article then proposes a task-specific authorization record naming responsible actors, permitted actions, operating conditions, exposed interests, and reassessment triggers, backed by independent scrutiny and by event records from which consequential decisions can be reconstructed. The procedure has a doctrinal pedigree that the Article makes explicit. Its first threshold restates the rule that a private actor may not be given power over its rivals; its second, the requirement that a delegation be justified on a record; and its timing test, the principle that a retained veto which cannot be exercised in time is no retention at all.

Autonomy here means authority to select or execute an action without contemporaneous human approval. AI includes learned inference and automated planning, although autonomous controllers need not use machine learning. Conventional automation supplies a comparator and evidence about established controls. The legal question is when an action affects another actor or requires distinct permission, and which institution must govern that transition.

Risk-risk analysis supplies the comparative discipline for this inquiry. A measure that reduces one danger can create another, and withholding the measure can preserve risks that regulation was meant to prevent. The analysis must therefore reach the controls themselves. Human approval, disclosure, and certification require the same examination of consequences as the system they constrain. The framework developed by John Graham and Jonathan Wiener, and subsequently applied by Felgenhauer and colleagues, provides a basis for examining these effects.[^1] This Article asks how that comparison should govern authority over a particular class of action.

Delayed spacecraft operations and orbital collision avoidance provide the principal comparison. Debris capture introduces jurisdiction and ownership interests into the latter case. SETI then tests the limits of applying a framework for physical action to scientific claims. These selected settings expose different legal transitions.

The legal analysis begins with the Outer Space Treaty and the Liability and Registration Conventions. United States communications regulation and NASA software requirements supply narrower implementation examples. Their scope matters: a domestic licensing condition and an agency engineering requirement cannot become a worldwide obligation by analogy. The argument concerns the evidence and institutional arrangements needed to justify delegation.

Part II explains what risk-risk analysis contributes to a legal decision and develops the two-threshold decision procedure and its counterparts in the law of delegation. Part III identifies existing duties and the limits of their operational specification. Parts IV and V examine delayed spacecraft operations and orbital safety, including debris capture; Part VI tests the argument against SETI. Part VII proposes the task-specific authorization record, an authorization process that can be revised as its factual basis changes. Part VIII answers the objections that could require narrower permission or defeat a particular application. Part IX concludes.

## II. From Risk Classification to a Comparative Decision Procedure

### A. Define the Harm Before Naming the Quadrant

The risk-risk taxonomy distinguishes countervailing effects by whether the adverse outcome and the affected population remain the same. An offset introduces the same type of harm to the same population; substitution changes the harm; transfer changes the population; transformation changes both.[^2] The categories direct attention toward consequences that a narrowly framed regulatory mandate might overlook. The result of the comparison still depends on the seriousness and likelihood of those consequences, the alternatives available, and the legal interests at stake.

A classification is useful only after its baseline, endpoint, and population are fixed. Suppose automation reduces loss of a spacecraft through delayed response but introduces loss of the same spacecraft through an erroneous command. At that level, the countervailing effect is an offset. If an avoidance maneuver protects that spacecraft while increasing collision exposure for a neighboring satellite, the same class of physical harm is transferred to a different owner and potentially different service users. Whether an effect is a transfer therefore depends on where the analysis draws the population boundary. Aggregating every space user into one population can hide a distributional conflict that disaggregation reveals.

Ground-team deskilling illustrates the distinction between a mechanism and the bearer of its ultimate harm. The people whose skills decline need not be the people who ultimately suffer a casualty or lose an asset. Skill erosion is initially a causal mechanism. If its consequence is a greater chance of injury to the same crew, the physical endpoint remains with that crew. If the claim instead concerns employment, professional development, or occupational status, it must identify and justify that different endpoint. Relabeling the operators as a different population does not establish a transfer of the original injury.

The same discipline applies to SETI errors. Missing a signal and falsely elevating interference are different events, although both can be grouped under scientific error. If the target harm is specifically a lost discovery, a false positive becomes relevant through a further pathway: it may absorb scarce telescope time, displace more promising candidates, or create a misleading public claim. The analysis should state that pathway rather than assume that opposite classification errors are automatically commensurable, because labels cannot replace a theory of harm.

### B. Compare Institutions Against Feasible Baselines

The proper baseline is an existing or reasonably available workflow, including its automation, personnel, constraints, and failure modes. An ideal human with unlimited attention and instantaneous communications is not a feasible alternative. Neither is an error-free autonomous system. For a delayed mission, the comparison might include ground-planned command sequences, onboard crew action where a crew exists, a conventional protective controller, and a more adaptive planner restricted by separate command limits. In orbit, it must include existing orbit calculation and screening tools rather than characterize the alternative as purely manual observation.

For each arrangement, the decision maker should identify the target harm, the pathways through which intervention reduces it, and the pathways through which intervention creates new burdens. The same inquiry applies to regulation. A requirement for individual approval may reduce erroneous commands but create delay, overload reviewers, or encourage routine approval without meaningful scrutiny. A certification requirement may reveal defects but consume resources otherwise available for tracking, redundancy, or collision coordination. A disclosure requirement may improve external scrutiny while exposing information useful to an adversary. The task is to evaluate these mechanisms comparatively, because innovation and regulation each carry costs as well as benefits.

Distribution remains a separate question. A maneuver that saves its operator substantial money while imposing smaller losses on many others may look beneficial in aggregate without being legally authorized or fairly allocated. Unconsenting third parties, users dependent on satellite services, and future entrants into a damaged orbital environment cannot simply be treated as residual terms in the operator's objective. Risk-risk analysis identifies these interests; applicable rights and duties constrain how they may be traded. A positive private estimate of total benefit leaves ownership and other legal protections in force.

### C. Identify the Point at Which Review Can Still Change the Outcome

The value of individual human review depends on an opportunity to intervene. Review must arrive before the decision becomes practically irreversible, provide information that can expose a material error, and be performed by someone with competence and authority to change the result. A reviewer who cannot meet those conditions may add little protection. Requiring approval can nevertheless preserve a formal chain of command; the question is whether that institutional benefit justifies the resulting delay and whether a better arrangement could preserve accountability upstream.

This approach is consistent with philosophical work on meaningful human control, which connects system behavior to relevant human reasons and traces responsibility to people who understand and shape the system. That literature does not make a contemporaneous approval step sufficient for control, nor does it supply a binding rule for spacecraft operations.[^3] Its value here is to separate the time of an action from the time at which accountable humans structure it.

The decision procedure this Article proposes therefore has two thresholds. First, does the actor have authority to undertake the activity and impose the relevant exposure? Second, does the evidence justify delegating this class of action under these conditions? Evidence satisfying the second threshold cannot substitute for the first. Where both thresholds are met, individual review should be required when its expected protective contribution is credible and timely. Where review is infeasible, the choice becomes advance-constrained action, a justified fallback, or withholding permission for the activity altogether. The absence of time to ask is not, by itself, a reason to authorize unrestricted autonomy.

Each element of that procedure has a counterpart in the law that governs delegation among human institutions. The first threshold corresponds to the oldest objection to private delegation. The Supreme Court called a statute that let one group of producers set terms for their competitors "legislative delegation in its most obnoxious form," because the power ran to private persons whose interests may be adverse to those of others in the same business.[^4] An operator whose maneuver policy moves risk onto a neighboring operator exercises power of that kind, and a better predictor does not answer the objection. The second threshold corresponds to the requirement of reasoned decision: an agency must "examine the relevant data and articulate a satisfactory explanation for its action," and it acts arbitrarily when it has "entirely failed to consider an important aspect of the problem" or an obvious alternative.[^5] The timing test corresponds to the law of subdelegation, under which an agency may rely on an outside party's work so long as it keeps the final decision for itself.[^6] A final decision that arrives after the action is complete is kept in name only. When review cannot change the outcome, the principal's judgment has to be exercised earlier and embodied in bounded terms, which is what an advance authorization of an action class does.

## III. Existing Law Governs the Actors but Leaves Operational Choices

### A. International Responsibility and Continuing Supervision

The Outer Space Treaty supplies the first legal constraints on delegated space activity. Article VI makes states internationally responsible for national activities in outer space and requires authorization and continuing supervision of nongovernmental activities. Article VII addresses international liability through launch-related connections. Article VIII preserves jurisdiction and control for the state of registry and provides that ownership is not displaced by an object's presence in outer space. Article IX imposes due regard and provides for prior international consultation when its specified potentially harmful interference conditions arise.[^7]

These provisions matter to autonomy without prescribing a controller architecture. An operator cannot infer from the absence of the word "algorithm" that its activity falls outside supervision. Article VI prescribes no cadence of individual command approval. Its requirement of continuing supervision must be given effect throughout an activity, including when software executes commands. Advance authorization can serve that requirement only if the responsible state retains a credible means of learning about material changes and acting on them. The treaty text leaves difficult questions about the appropriate state for a multinational activity and the distribution of domestic functions. An operator's chosen architecture cannot resolve those questions for the states concerned.

International adjudication supports reading continuing supervision as a duty that moves with the facts. The Seabed Disputes Chamber has described a sponsoring state's obligation to ensure a contractor's compliance as an obligation "of conduct" and of "due diligence," and has called due diligence "a variable concept" that "may change over time" with new scientific or technological knowledge and "in relation to the risks involved in the activity."[^8] The International Law Commission's articles on prevention draw the procedural consequence: prior authorization for a hazardous activity, fresh authorization for any major change, and termination where the terms of authorization are not met.[^9] Reassessment triggers and revisable permissions are therefore what due diligence ordinarily requires of a supervising state, and Part VII applies them to delegated execution.

International responsibility also needs to be distinguished from the proposition that every private command is attributable to a state under ordinary attribution rules. The International Law Commission's articles separately address attribution and breach, and recognize that special rules may govern the conditions or consequences of responsibility.[^10] Article VI expressly addresses national activities by governmental and nongovernmental entities. The treaty analysis should begin with that obligation, without treating a private actor's use of autonomous software as either automatic general-law attribution or an escape from the state's space-law duties. For present purposes, the relevant obligation is the state's responsibility to assure treaty conformity and supervise the national nongovernmental activity. A damages claim presents further questions under the separate liability regime.

Article IX requires due regard for other states parties' corresponding interests. Where a state has reason to believe that a planned activity by it or its nationals would cause potentially harmful interference with other states parties' peaceful exploration and use, it must undertake appropriate international consultations before proceeding. Another state party may request consultation when the stated conditions are met.[^11] Consultation supplies no express universal veto. Due regard also supplies no numerical collision threshold. The authorization mechanism proposed below is an implementation choice designed to give these duties practical effect by requiring consideration of external exposure.

### B. Liability Supplies Incentives but Incomplete Prevention

The Liability Convention distinguishes two kinds of covered damage. For damage on Earth's surface or to aircraft in flight, launching-state liability is absolute. For damage elsewhere to another launching state's space object, or to persons or property aboard it, Article III applies a fault standard. Article I defines damage in terms of death, injury or impaired health, and property loss or damage. Article VI provides specified conditions for exoneration from absolute liability. These distinctions prevent a single characterization of all space harm as either strict liability or an unregulated technological accident.[^12]

The Convention's remedies have significant limits. Claims proceed through states and diplomatic channels. Article XI preserves domestic proceedings, subject to its restriction on concurrent pursuit of the same damage, but creates no universal private cause of action. A Claims Commission's award binds the parties only if they have so agreed; otherwise it is recommendatory. Article VII excludes launching-state nationals and specified participants or invited persons. A lost scientific opportunity or diffuse environmental interest without a clear connection to covered damage raises an additional scope question.[^13] These limits affect the incentives and accessibility of compensation even though the underlying treaty obligations remain binding.

Autonomous execution can complicate proof of fault without eliminating the relevant state or operator. Article III refers to fault of the launching state or persons for whom it is responsible. An argument that the machine is not a legal person does not establish immunity for negligent design, delegation, maintenance, or use. The text leaves room to examine failures of design, maintenance, delegation, and use by the relevant actors.[^14] It does not settle the precautions an autonomous maneuver policy must take. That determination requires a standard of fault, proof of causation, and an account of the information and precautions reasonably available before the event. An inquiry confined to whether the final command was generated by a machine would miss the decisions that placed the machine in that position.

### C. Operational Detail Can Enter Through Different Institutions

Registration assists identification, but the Registration Convention's required information is not a complete operational record. It does not specify a log of model versions, maneuver permissions, or decision inputs.[^15] The COPUOS Long-term Sustainability Guidelines recommend supervision, contact and information exchange, improved orbital information, and conjunction assessment. They expressly remain voluntary under international law.[^16] Their existence nevertheless helps distinguish a technical coordination problem from an alleged vacuum of all norms.

Within its own licensing and market-access regime, the FCC requires covered applicants to disclose maneuverability and plans for sharing operational information. Its accompanying order identifies guidance and operations schemes and collision-avoidance thresholds as relevant disclosure details. Covered operators also certify that they will review conjunction warnings, assess collision risk, and mitigate where necessary, including appropriate coordination. The relevant information-collection provisions became effective in September 2024. The agency grounds its regime in domestic communications authority.[^17] Article VI does not itself confer general regulatory power on the FCC. The rule does not resolve every question about contemporaneous human review. An additional condition governing autonomy would need to fit the Communications Act and the lawful scope of the agency's licensing function.[^18] A useful safety condition does not supply missing statutory power. Where existing authority cannot sustain the condition, the proposal requires legislation or another competent institution.

That caution has become more pressing. Since 2024 a reviewing court decides for itself whether an agency has acted within its statutory authority and no longer defers to the agency's reading of an ambiguous statute.[^19] A condition on autonomous maneuvering would be tested against the text of the Communications Act by a court exercising independent judgment, which makes the choice of institution a first-order question for any proposal of this kind.

## IV. Delayed Spacecraft Operations and the Case for Advance Permission

### A. Latency Changes the Comparator

Communications delay creates a real constraint, but it does not make all ground expertise useless. A NASA analysis of prospective crewed Mars missions describes one-way delays reaching approximately twenty-two minutes, alongside disruptions and blackouts. It does not demonstrate that an AI system can safely manage every emergency arising during those intervals.[^20] Long-range planning can remain on Earth while local systems execute time-sensitive responses. Where a crew is present, onboard human judgment is a further comparator, distinct from delayed ground approval.

Consider a hypothetical spacecraft facing a rapidly worsening equipment fault. The target risk is loss caused by failure to respond within the available interval. Waiting for Earth may be infeasible. A preprogrammed protective response may be adequate if the fault is recognizable and the response's effects are understood. An adaptive planner becomes attractive only if it handles a relevant range of conditions better than that simpler alternative. Delegating that response requires evidence that the existing protective arrangements are inadequate.

The converse matters. A choice about a mission's scientific priorities may tolerate a delay even when a stabilization command cannot. The same spacecraft can thus support substantial execution autonomy and retain deliberative control over mission changes. Review should attach to the consequential transition, even where the same software performs both tasks.

### B. Flight Experience Supports a Narrow Claim

NASA's Deep Space 1 Remote Agent experiment demonstrated autonomous planning and execution for selected subsystems under high-level goals. The mission account also records a software bug that interrupted the first experiment before subsequent work completed the remaining objectives.[^21] This is evidence that meaningful autonomy can operate on a spacecraft and that integration failures remain relevant. Unrestricted crew-safety decisions by a general-purpose language model would need evidence of their own.

AEGIS provides a more sustained example of bounded scientific autonomy. The Curiosity study describes autonomous target selection using parameters supplied by scientists.[^22] A 2024 Perseverance paper describes adjustable target filtering and ranking, alongside separate flight-software protections against unsafe pointing or laser firing into rover hardware. Observations are invalidated when relevant mechanisms have moved after target selection, and deployment proceeded through testing and stages. A protective rejection can sacrifice an observation while protecting the instrument.[^23]

Those facts establish an important possibility: an action can occur without Earth reviewing each target while remaining constrained by decisions and safeguards established beforehand. The evidence does not establish that the same arrangement is safe for life support or maneuvering near another operator's satellite. The useful inference is architectural and limited. Advance permission can define a task, retain constraints outside the task-selection process, and end when facts underlying the selection have changed. Its success must still be demonstrated for each new application.

NASA's software requirements reinforce this distinction. Within their stated scope, they address safe states, input integrity, prerequisites for hazardous commands, and response within the time required to prevent a hazard. Applicability to contractors depends on the specified contractual setting.[^24] These requirements are a concrete institutional baseline against which an AI component should be assessed. Compliance remains a baseline for evaluating the added component, whose hazards require assessment within the mission.

### C. Compare the Burdens of Three Arrangements

Universal ground approval is weakest where its response arrives after the relevant opportunity. It can preserve records and centralized judgment, but those benefits must be compared with the loss caused by waiting. Unrestricted onboard delegation removes that delay but may allow a planning error to propagate into activities never evaluated by the mission's assurance process. Advance permission for specified actions occupies a defensible middle position only when its boundaries and fallback behavior are credible.

For the hypothetical fault, the permission should identify the observations on which the response depends, permissible commands, resource limits, forbidden effects, and conditions requiring a different mode. The fallback might be a protective action rather than passivity. A spacecraft on an unsafe trajectory does not become safe merely by declining to decide. The appropriate fallback must be established through the dynamics and hazards of that mission; calling it a "safe mode" supplies no proof.

United States launch regulation already contains a rule of this form. A licensed operator must "determine and use flight safety limits that define when an operator must initiate flight abort," the vehicle data needed to evaluate its abort rules "must be available to the flight safety system," and a flight need not be aborted where abort "would not materially decrease the risk from a high consequence event."[^25] The regulation delegates a drastic action to limits set in advance, and it treats the fallback as a choice whose risks have to be compared with those of continuing.

Protective limits also create countervailing losses. A rejected observation may be scientifically valuable. A conservative response may consume scarce resources or shorten the mission. An unnecessary demand for explanatory text may add computation or distract an operator without improving command validity. None of these costs establishes that the limits should be removed. They show why assurance must compare actual outcomes and explain why particular sacrifices are warranted. A mission may reasonably prioritize preservation of an instrument over one observation while choosing a different balance for a unique, time-limited measurement.

Onboard power and thermal costs depend on hardware, inference workload, duty cycle, and the functions displaced. The permission inquiry should address those costs within the particular mission. Terrestrial model-training expenditure cannot establish the burden of executing a narrow model aboard a spacecraft.

Human authority remains essential at other points. People must approve mission objectives, review material changes, understand what a protective response sacrifices, and investigate unexpected outcomes. For a crewed vehicle, the allocation of authority must also consider crew knowledge and the consequences of an erroneous override. The proposal leaves the safety value of an accessible override to be shown: it requires evidence about the intervention that particular humans can actually perform.

The flight evidence supports task-specific scientific selection under demonstrated protections. Requiring Earth to approve each protected selection would surrender the opportunity the system was designed to use without identified additional protection. Extending the permission to crew life support would require separate evidence about a substantially different hazard and task.

## V. Orbital Safety and Risks Imposed on Other Operators

### A. A Better Prediction Is Only One Part of Avoidance

Orbital collision avoidance presents a harder case because the operator's objective and the safety of the surrounding environment can diverge. The operational sequence includes detecting and tracking objects, estimating their future states and uncertainty, screening conjunctions, selecting a response, coordinating where possible, executing the command, and evaluating the resulting trajectory. Different systems may perform different steps. Better performance at an early step does not establish safe completion of the sequence.

The ESA spacecraft collision-avoidance challenge illustrates this distinction. The competition used earlier conjunction data messages to predict the estimated risk in the final available message. Its target was thus another risk estimate rather than observed collisions or measured harm avoided. The authors discussed class imbalance, generalization problems, and limitations of evaluation practices.[^26] Those findings support development of forecasting tools. Whether a high-performing predictor can safely choose and execute maneuvers in a multi-operator environment is a further question, and prediction scores leave it open.

The appropriate baseline is therefore current screening and operator-led coordination, with the limitations of its data and response process acknowledged. The alternatives are universal individual approval, operator-controlled automation, and automation constrained by validated limits and coordination obligations. A centralized controller directing every satellite is another conceptual alternative, but it demands authority, information, and international participation that cannot be assumed. An institutional comparison must charge that alternative with its own establishment costs and failure modes.

Routine conjunction management can provide time for human assessment; the ESA challenge used a planning horizon measured in days.[^27] The case for advance emergency authority concerns later information or operational constraints that leave insufficient time for useful review. The frequency of those exceptional orbital conditions remains a separate empirical question. On the evidence reviewed, forecasting assistance is justified more readily than independent maneuver execution. The latter needs a policy-level assurance case beyond prediction performance; routine approval and coordination remain reasonable where they can improve the decision in time.

### B. Collision Avoidance Can Redistribute Exposure

Suppose two operators receive warnings about a close approach. Each can move, but each estimates the other's future motion imperfectly. A maneuver selected to reduce one conjunction may change exposure elsewhere. These are hypothetical mechanisms for evaluating a policy, not accounts of a verified AI-caused collision. Orbital avoidance therefore requires analysis of interactions absent from a solitary spacecraft's response to a local fault.

State practice has supplied an instance. In December 2021 China informed the Secretary-General that its space station had twice carried out "preventive collision avoidance control" after close encounters with Starlink satellites, and that on the second occasion, because the satellite "was continuously manoeuvring, the manoeuvre strategy was unknown and orbital errors were hard to be assessed." The note closed by quoting Article VI. The United States replied that its Space Command "did not estimate a significant probability of collision" and that, because the encounters "did not meet the threshold of established emergency collision criteria, emergency notifications were not warranted."[^28] The two states did not disagree about physics. They disagreed about whose threshold governed and about what one operator is owed concerning another's maneuver policy, which are the questions an authorization record is meant to answer in advance.

For the first operator, automation may reduce delay and preserve its spacecraft. A wrong estimate or inappropriate command can offset that benefit through damage to the same asset. Maneuvering may consume propellant otherwise available for later avoidance or disposal, introducing a further causal pathway to future harm. If a new trajectory increases another operator's collision exposure, the policy transfers part of the physical risk. If disclosure of sensitive operational data creates a separate security vulnerability, that is a different endpoint requiring its own evidence and safeguards. Each pathway should be evaluated for the decisions and precautions it changes.

Population definitions alter the recommendation. An operator may prefer a response that maximizes its remaining mission life; users dependent on another satellite may value continuity elsewhere. A state evaluating its national industry may discount losses outside its jurisdiction. An orbital environment with more debris can impose burdens on later entrants who had no role in the initiating decision. A private operator's willingness to accept its own residual risk does not resolve those conflicts. Neither does a human employee's approval convert imposed risk into consent.

The proposed authorization should accordingly require a comparative justification at the level of the maneuver policy, not only the predictor. The applicant should explain how it screens the proposed trajectory, accounts for uncertain or missing information, avoids mutually inconsistent responses where coordination is possible, and responds when communications fail. A relevant assurance exercise would test misleading alerts, stale estimates, simultaneous maneuvers, and loss of the expected coordination channel.

Human review is especially valuable before an operator expands the range of maneuver types, changes its objective, or begins relying on a materially different information source. It may be valuable for a particular conjunction when sufficient time remains and the reviewer can obtain information absent from the automated process. Where the final opportunity is too short, requiring approval can defeat the protective purpose. Such cases justify an advance-specified emergency policy only if the policy itself has been justified. An operator should not be allowed to create avoidable urgency through poor planning and then treat urgency as a general waiver.

### C. Individual Safety Constraints Do Not Establish Collective Safety

Work on runtime assurance for autonomous spacecraft inspection provides a technically serious way to constrain proposed commands. Dunlap, van Wijk, and Hobbs compare centralized and decentralized approaches. In their simulations, decentralized filters sometimes could not satisfy a sensor Sun-exclusion constraint because assumed acceleration was unavailable when constraints conflicted. The authors discuss modifying or relaxing that constraint as mitigation.[^29] The evidence concerns specified dynamics and tradeoffs in simulation. Observed commercial-satellite collisions and safety across the orbital population lie beyond it.

Its institutional implication is conditional but important. A license for one operator's policy must consider interactions with other permitted policies. Regulators and operators should make their relevant assumptions compatible where possible: how intended maneuvers are communicated, when information expires, and what each party expects the other to do. Interoperable information and predictable protocols may improve safety more than requiring every participant to use the same prediction model. Mandating a common model could instead concentrate a shared error.

The older transport regimes mark the same distinction. Vessels at sea avoid collision under rules that assign each encounter a give-way vessel and a stand-on vessel; neither is told how to predict the other's course.[^30] Airborne collision avoidance coordinates complementary maneuvers between two aircraft, and the collision over Überlingen in 2002 occurred when one crew followed a controller's instruction against the system's advisory.[^31] What these regimes share is a common protocol for who moves and how intentions are signaled, with prediction left to each participant. Orbital operations have the predictors and lack the protocol. A licensing condition should therefore ask for interoperable right-of-way rules and maneuver-intent messages before it asks for any particular model.

Sensitive telemetry need not be broadcast universally. A competent institution could receive detailed information while other operators receive the minimum timely information needed to coordinate. That proposal has costs: trusted intermediaries can fail, withhold information, or become attractive targets. The tradeoff should be explicit, and the fallback should not depend on an information service that the operator has no reliable right or ability to use.

### D. Capture Changes Both the Physical Act and the Legal Interest

Active debris removal adds a boundary that collision forecasting cannot cross. Changing one's own trajectory differs from approaching, attaching to, controlling, and disposing of another actor's object. RemoveDEBRIS demonstrated specific technologies using mission-provided experimental targets. Its full report describes an unsuccessful drag-sail outcome as well as successful components.[^32] Routine, safe removal of arbitrary legacy debris remains to be shown. So does the complete sequence from identification through disposal, of which a laboratory controller or a successful capture mechanism covers one part.

Article VIII makes it unsafe to assume that labeling an object "debris" extinguishes ownership or registry-state interests. The treaty is not a detailed salvage code, and the applicable consent arrangements require mission-specific legal analysis. Nevertheless, an algorithmic risk ranking cannot itself supply authority to take control of the selected object.[^33] The distinction is independent of whether a human would choose the same target.

A proportionate process would separate authorization of the target and removal plan from time-sensitive execution within that plan. Before close approach, the responsible parties should resolve the relevant consent and authority questions, identify the target, consider plausible failure trajectories, and establish the conditions permitting capture. At the execution stage, validated abort or separation responses may need to occur automatically. Stopping for a new human signature during a rapidly developing proximity hazard could undermine the advance safety plan.

The plan should also compare removal with less interventionist alternatives. Monitoring, avoiding, or postponing action may preserve options; leaving a hazardous object in orbit also carries costs. Removal can fail during capture or disposal and may redistribute exposure toward reentry locations or other orbital users. A case for intervention therefore requires evidence about the chosen object and method, rather than reliance on the general proposition that debris is dangerous. The same framework can justify a particular removal mission and reject another.

This case exposes the limits of autonomy regulation standing alone. It cannot decide all questions of orbital access, target prioritization, compensation, and international security. It can require that those decisions be made by identifiable actors with relevant authority before a machine is permitted to implement them. That requirement improves the law by making the boundary between deciding and executing visible and contestable.

## VI. SETI and the Difference Between a Candidate and a Conclusion

SETI tests whether a framework built around physical action becomes overbroad when applied to knowledge production. Recognizing whale calls in long-term acoustic recordings is a tempting model for identifying an extraterrestrial signal. That research worked from known-species evidence and from matched visual and acoustic observations, so what it offers SETI is a method for sorting and prioritizing signals.[^34] Interpreting the meaning of an unknown communication system would require evidence of a different kind.

The more relevant evidence is Peter Ma and colleagues' search of observations from 820 nearby stars. Their machine-learning pipeline used synthetic signal injections and produced candidates that underwent further filtering and visual inspection. Eight signals were selected for examination, and follow-up did not redetect them. Reported test performance concerns the specified simulated task, not a measured probability that a candidate is extraterrestrial.[^35] Machine learning supplied a different route for prioritizing observations within that search design.

The blc1 candidate demonstrates the need for further investigation. Sheikh and colleagues attributed it to local electronic interference and developed a verification framework.[^36] A candidate can survive initial screening while its origin remains unresolved. Claims that such an error would cause diplomatic escalation require additional evidence about how institutions would respond.

The target harm should be defined as lost or distorted scientific knowledge under limited observing and analytical capacity. The baseline already contains extensive data reduction and automated analysis.[^37] The choice is not between AI and humans listening unaided. A useful comparison asks which search policy identifies worthwhile candidates, which kinds of signals it may systematically miss, and how follow-up capacity is allocated. Raising a screening threshold reduces workload but may suppress unusual evidence. Lowering it can overwhelm follow-up resources. Without a confirmed corpus of extraterrestrial signals, synthetic tests cannot determine real-world sensitivity to all possible technosignatures.

A staged process is preferable to either automatic confirmation or universal political preclearance. Automated systems may identify and circulate candidates within a documented research process. An institution asserting confirmed extraterrestrial origin should require accountable scientific examination of alternative explanations, evidence from independent instruments or observations where feasible, and disclosure of the basis and limits of the conclusion. The word "independent" matters: several people reviewing the same model score do not create additional observational evidence.

This requirement concerns an institution's endorsement of a confirmation claim. It does not confer power to license scientific truth or prevent competing interpretations from being published. Independent criticism remains part of verification, including criticism of the institutions that claim to have completed it.

The International Academy of Astronautics' 2010 declaration provides an existing professional precedent. It distinguishes handling candidates, verification, confirmed announcements, and preservation of observations. Principle 8 commits signatories to seek the guidance and consent of a broadly representative international body before responding to a confirmed signal. The declaration is a voluntary commitment by individuals and institutions.[^38] It supports scientific coordination without establishing a treaty-based power for the United Nations to approve every research communication.

A difficult question remains about releasing unconfirmed observations. Premature certainty can mislead, but delay may prevent another observatory from investigating a transient event. The proposed distinction is between circulating evidence with explicit candidate status and publicly certifying an interpretation. The 2010 declaration itself discourages premature disclosure while protecting transparent scientific activity. The present recommendation would operationalize that tension through prearranged scientific circulation and careful public labeling, rather than treat the protocol as an unambiguous command to publish every candidate immediately.

Observatories and research funders could adopt provenance, preservation, and reporting conditions suited to their relationships with investigators. Such conditions would need to respect applicable law and scientific freedom. A supervisory power over national space activities does not automatically establish governmental authority over a terrestrial research team's interpretation or speech. Proposed restrictions on communication would require their own legal basis and justification. This limit is a reason to prefer scientific verification arrangements for scientific claims over borrowed spacecraft licensing powers.

In the United States the limit is constitutional as well as jurisdictional. A requirement that an announcement be cleared in advance would be a prior restraint, and "[a]ny system of prior restraints of expression comes to this Court bearing a heavy presumption against its constitutional validity."[^39]

Transmission of a deliberate response is a further act, distinct from detecting, interpreting, or reporting. Classifier performance supplies no evidence about the effects of a deliberate response. Permission to search cannot, by itself, authorize an institution to speak for humanity or choose that response. With those decisions separated, institutions retain the benefit of automated search and refuse to infer new authority from technical success.

## VII. Implementing Authority That Can Be Revised

### A. A Task-Specific Authorization Record

This Article proposes a concise authorization record for a defined activity, supported by a proportionate assurance case. It should state the actor, the action class, the operating conditions, the interests exposed, the feasible alternatives considered, and the conditions that require fresh review. It should also identify what the system must do when its authorization no longer fits the situation. The record is a legal and operational instrument; it need not reveal source code to every affected party or require a new certificate for every routine command.

For a spacecraft instrument, the record might authorize selection within specified parameters while reserving changes to scientific goals or hazardous operating conditions. For avoidance, it might authorize a set of maneuver policies with data-quality, coordination, and trajectory constraints. For capture, it should identify the target and legal permissions separately from execution limits. For SETI, the analogous institutional record would distinguish candidate generation, scientific confirmation, and communication responsibilities. These examples apply the same questions through different institutions rather than a universal space-AI regulator.

Evidentiary burdens should reflect access to information. An applicant should explain why existing arrangements are insufficient and produce evidence about the proposed capability and its limits. The regulator should justify conditions addressing material risks and explain why less burdensome precautions are inadequate. Neither must prove zero risk. Serious external effects without a credible basis for the proposed operating range can justify refusal or postponement.

### B. An Independent Opportunity to Challenge the Authorization

Advance review can fail if the beneficiary defines the test, controls the evidence, and treats approval as final. For materially consequential external effects, the authorization process should include technical scrutiny with sufficient independence to challenge the baseline and excluded scenarios. The form can vary with the activity: an agency's assurance function, a separately accountable reviewer, or a shared technical service subject to oversight. Small operators should be able to rely on reusable test facilities and common evidentiary formats where those are valid for their missions.

Independent scrutiny is not synonymous with unrestricted disclosure. Public justification can explain the action class, protected interests, and reasons for the decision while controlled access protects sensitive details. Those directly positioned to identify an omitted risk should have a route to raise it with a competent decision maker. This proposed procedural safeguard is especially important when one operator's claimed efficiency depends on another operator accommodating its behavior.

Authorization should remain revisable. Changed software affecting permitted behavior, a materially different environment, or evidence that data assumptions no longer hold should trigger reassessment. Specifying triggers in advance permits the operator to distinguish changes requiring fresh approval from maintenance that leaves the justification intact.

For example, a proposed proximity-operation authorization could name the responsible operator supervisor and require the onboard system to inhibit further approach when validated state-estimation conditions fail, while executing a separately tested contingency suited to the geometry. It would preserve the event record and notify the supervisor at the next available contact. Resumption would require documented restoration of the relevant conditions; a material expansion of the operating range would return to the authorizing institution. The contingency's risks must also be justified. Temporarily inhibiting an operation is an engineering action, distinct from legally revoking the mission's authority.

### C. Records of Consequential Decisions

Operational records should make it possible to reconstruct consequential decisions: the relevant observations and uncertainty, applicable software and policy versions, permitted action range, selected action, interventions, and information exchanged with other actors. Not every raw datum must be retained indefinitely. Retention should reflect the activity, investigation needs, applicable claim periods, storage constraints, and privacy or security interests. For SETI, preserving the underlying observations can matter more than preserving the model's prose explanation.

Records can reveal recurring conditions that an authorization failed to consider and distinguish compliance with a defensible plan from disregard of a known limitation. They leave the legal standard of fault and proof of causation to be determined. An explanation generated after the event carries little weight unless it can be tied to the information and process that produced the action.

The record also connects supervision before the event to liability after it. A fault standard requires an account of the precautions reasonably available before the event, and that account is what claimants under the Liability Convention have lacked. A documented operating range supplies it. Departure from the range is evidence of fault, in the way a violated safety standard is evidence of negligence, and operation within it is evidence of care without being a defense, as compliance with a statute is in the common law of torts.[^40] The authorization record thus gives the liability regime the proof it has been missing, and the two forms of control reinforce each other.

Suppliers should provide operators with the information and change notices needed to satisfy these obligations. Contracts can allocate audit access, cooperation, and recourse among private parties. Such arrangements should not be described as rewriting the launching states' treaty obligations. They may improve internal incentives while leaving the international claimant's rights and applicable domestic law unchanged. The operator should remain answerable for the decision to integrate and use a component within its authorization, while supplier responsibility depends on the governing legal and contractual rules.

### D. Use Existing Institutions Without Overstating Their Powers

For covered communications satellites, FCC disclosures provide a concrete starting point for asking applicants to describe autonomous maneuver policy and its assumptions. The 2024 reconsideration is instructive: the agency declined to preserve an assumption of zero or near-zero collision risk where the record showed insufficient avoidance capability.[^41] A favorable modeling convention is not a finding that autonomy eliminates risk. Further requirements would still need a lawful rulemaking or other applicable process and a reasoned connection to the FCC's statutory responsibilities.

NASA can use its applicable engineering and acquisition arrangements for its missions. Other national authorities would require their own legal basis. COPUOS guidelines can support interoperable practices without being misrepresented as compulsory global regulations. A new international agreement may eventually be desirable for unresolved coordination or removal questions, but its negotiation is not a prerequisite for every operational improvement. The immediate question is which competent institution can implement a particular safeguard and be held responsible for its performance.

## VIII. Objections and the Risks of Regulation

### A. The Authorization May Conceal the Real Political Choice

The strongest objection is that a technically impressive assurance case can disguise a contested allocation of public risk. An operator may select favorable scenarios, omit remote harms, and gain certification from reviewers dependent on industry expertise or fees. Once operations scale, withdrawal can become politically difficult. The record could conceal the contested allocation beneath a finding of technical compliance.

The objection reaches the conditions of legitimate permission, and the proposal meets it on those terms. The authorization must identify whose losses are excluded or uncertain, disclose the basis for material tradeoffs, and remain open to revision. Compliance should not create immunity or conclusive proof of due care. A reviewer must be able to challenge the activity's scale and objective, not only the model's accuracy. Where a mission's economics depend on imposing unacceptable external effects, narrower software permissions will not make it legitimate. The appropriate response may be to constrain the activity itself.

### B. Regulators May Make Safe Action Slower and More Expensive

A second objection is that elaborate assurance favors incumbents. Documentation, specialist review, and repeated approval can consume the resources of smaller operators and delay technologies that would reduce existing hazards. Continuous reauthorization may discourage correcting a flawed system. If the proposal requires every operator to reproduce expensive tests, it may reduce diversity and strengthen dependence on a few vendors.

The costs of those requirements depend on the institution and mission. Review should therefore compare the proposed requirement with less burdensome precautions that can accomplish the same protective purpose. Common test resources, reusable evidence for shared components whose use and conditions are equivalent, recognition of equivalent review, and focused reassessment of material changes can reduce burdens. The regulator should explain what additional harm a requirement prevents and what lower-cost alternative was rejected. COPUOS guidance expressly supports examining costs, time, risks, and feasible alternatives and seeking affected entities' input when developing regulation.[^42] The guidance expressly makes regulation itself an object of comparison.

The comparison has to run in both directions. Risk-tradeoff analysis as usually practiced counts the harms a regulation causes and neglects the benefits it produces beyond its stated aim.[^43] Approval, certification, and disclosure have such benefits. Records kept for supervision later support claims and investigations, assurance exercises train the operators who run them, and a decision that can be reconstructed deters carelessness. A regulator applying this Article's procedure should enter those benefits in the same ledger as the delay and expense.

Proportionality requires the evidence and process to track the consequences and uncertainty of the action. Shared infrastructure may lower the cost of producing that evidence, but high compliance costs cannot justify unlimited exposure of other operators. Where no proportionate control makes the activity defensible, the conclusion is a limit on permission.

### C. A Validated Boundary May Fail Outside Its Assumptions

A third objection concerns technical and institutional common failure. A monitor may rely on the same flawed sensor or state estimate as the controller. A fallback can become unsafe under unexpected dynamics. Multiple operators can each satisfy local constraints while their combined actions remain dangerous. These possibilities make the language of a "safety envelope" misleading if it is understood as a guarantee.

The failure has occurred in flight. In NASA's 2005 DART mission an autonomous rendezvous vehicle collided with its target although its collision-avoidance function had activated, because "[t]he software logic for collision avoidance was dependent on the same navigational data source as the guidance system."[^44] A protection that shares the controller's picture of the world protects only against errors the controller does not make.

The proposal answers this objection by requiring an operating range justified by evidence rather than treated as a guarantee. Independence of a protective component must be assessed against actual failure pathways, rather than inferred from a different software module name. Validation should include adverse interactions and plausible losses of information. Where changed conditions cannot reliably be detected, permission may need to be narrower. Evidence of severe, unbounded common failures would support withholding a class of autonomous action even if its average performance were attractive.

An operating range whose limits cannot be observed may be incapable of supporting permission. It would be insufficient to show that constrained autonomy usually works while its bounds become unobservable precisely when catastrophic harm is possible. A comparison may then favor a simpler controller, a different mission design, human judgment with sufficient time, or no deployment. The framework selects among those options according to the evidence.

### D. Liability Alone or Global Control Might Be Preferable

One alternative is to rely primarily on liability and insurance. Actors facing the full cost of their choices have incentives to select efficient precautions without detailed regulatory review. That argument is strongest where harm is compensable, causation can be shown, assets or insurance can meet the claim, and injured parties can obtain a remedy. The treaty distinctions discussed above, together with the possibility of diffuse orbital or scientific losses, weaken any assumption that those conditions always hold. Liability remains valuable as a complement to preventive coordination.

Another alternative is a single international body assigning maneuvers and adjudicating conflicts. It could internalize effects that national supervision misses. Yet centralized authority would require reliable access to sensitive information, legitimate allocation rules, adequate technical capacity, and safeguards against its own failures. Whether such an institution would outperform national supervision depends on its authority, information, and failure modes. Interoperable protocols and accountable national implementation offer an incremental course, but they retain coordination conflicts that each authorization must address.

Finally, reduced risk per action may encourage more activity. Additional maneuvers, satellites, or interventions could erode gains measured at the individual-task level. Supervisory evaluation should account for that possible response: fewer false alarms or better execution per maneuver does not establish that total public exposure has fallen. Permission to automate a task should not silently become permission to expand the scale of the underlying activity.

## IX. Conclusion

The law of autonomous space activity should attach responsibility to the decisions that grant and shape authority. Delayed operations can justify advance permission for validated local action. Orbital avoidance adds coordination and third-party exposure. Capture adds legal interests that prediction cannot resolve. SETI requires a distinction between searching, confirming, communicating, and responding. The procedure asks of an autonomous system what the law already asks of any delegate: authority first, a justification on the record, and control exercised while it can still matter.

Existing law already governs the actors and many of the interests at stake. Its incompleteness calls for operational specification, lawful implementation, and reconstructable evidence, rather than an assumption that every technological change requires a new treaty. The proposed authorization is task-specific, revisable, and open to challenge. It gives no immunity for conduct inside a nominal boundary and no permission for conduct beyond the actor's legal authority.

Risk-risk analysis requires evaluation of the controls themselves. Human review, certification, information sharing, and restrictions all impose costs and can create hazards. A defensible arrangement explains why its combination of action and restraint is preferable to feasible alternatives, for the people who actually bear the consequences. A permission resting on assumptions that can no longer be defended should be narrowed, transferred to an adequately supported alternative, or withdrawn.

---

## Notes


[^1]: TYLER FELGENHAUER ET AL., SOLAR RADIATION MODIFICATION: A RISK-RISK ANALYSIS 13-16 & tbls. 1-2 (2022), https://www.c2g2.net/wp-content/uploads/202203-C2G-RR-Full.pdf. *See generally* RISK VS. RISK: TRADEOFFS IN PROTECTING HEALTH AND THE ENVIRONMENT (John D. Graham & Jonathan B. Wiener eds., 1995).

[^2]: FELGENHAUER ET AL., *supra* note 1, at 13-16 & tbls. 1-2.

[^3]: Filippo Santoni de Sio & Jeroen van den Hoven, *Meaningful Human Control over Autonomous Systems: A Philosophical Account*, 5 FRONTIERS ROBOTICS & A.I. art. 15, §§ "Tracking," "Tracing" (2018).

[^4]: Carter v. Carter Coal Co., 298 U.S. 238, 311 (1936).

[^5]: Motor Vehicle Mfrs. Ass'n of the U.S., Inc. v. State Farm Mut. Auto. Ins. Co., 463 U.S. 29, 43, 46-51 (1983).

[^6]: U.S. Telecom Ass'n v. FCC, 359 F.3d 554, 565-68 (D.C. Cir. 2004).

[^7]: Treaty on Principles Governing the Activities of States in the Exploration and Use of Outer Space, Including the Moon and Other Celestial Bodies arts. III, VI-IX, Jan. 27, 1967, 18 U.S.T. 2410, 610 U.N.T.S. 205 [hereinafter Outer Space Treaty].

[^8]: Responsibilities and Obligations of States Sponsoring Persons and Entities with Respect to Activities in the Area, Case No. 17, Advisory Opinion of Feb. 1, 2011, 2011 ITLOS Rep. 10, ¶¶ 110, 117.

[^9]: Int'l Law Comm'n, Draft Articles on Prevention of Transboundary Harm from Hazardous Activities art. 6, *in* Rep. of the Int'l Law Comm'n on the Work of Its Fifty-Third Session, U.N. Doc. A/56/10 (2001).

[^10]: Int'l Law Comm'n, Draft Articles on Responsibility of States for Internationally Wrongful Acts, with Commentaries, arts. 2, 4, 8, 55, *in* Rep. of the Int'l Law Comm'n on the Work of Its Fifty-Third Session, U.N. Doc. A/56/10 (2001), *reprinted in* [2001] 2 Y.B. Int'l L. Comm'n 31, 34, 40, 47-48, 140-41. The articles address general responsibility rules and their relationship to special regimes; the application to Article VI is the analysis advanced here.

[^11]: Outer Space Treaty, *supra* note 7, art. IX.

[^12]: Convention on International Liability for Damage Caused by Space Objects arts. I-III, V-XII, XIV-XIX, Mar. 29, 1972, 24 U.S.T. 2389, 961 U.N.T.S. 187 [hereinafter Liability Convention].

[^13]: *Id.* arts. I, III, VII-XI, XIX.

[^14]: *Id.* art. III.

[^15]: Convention on Registration of Objects Launched into Outer Space arts. II-IV, VI, Jan. 14, 1975, 28 U.S.T. 695, 1023 U.N.T.S. 15.

[^16]: Comm. on the Peaceful Uses of Outer Space, Rep. of the Comm. on the Peaceful Uses of Outer Space, annex II, pmbl. ¶¶ 14-16, guidelines A.2-A.3, B.1-B.4, at 52, 55-56, 59-61, U.N. Doc. A/74/20 (2019) [hereinafter LTS Guidelines].

[^17]: Mitigation of Orbital Debris in the New Space Age, 85 Fed. Reg. 52,422, 52,424-25, 52,429-30, 52,432-33, 52,451 (Aug. 25, 2020) (codified at 47 C.F.R. § 25.114(d)(14)(iv)(A)(4)-(5), (v)(C)); Space Innovation; Mitigation of Orbital Debris in the New Space Age, 89 Fed. Reg. 65,217, 65,217 (Aug. 9, 2024) (announcing Sept. 9, 2024 effective date).

[^18]: Mitigation of Orbital Debris in the New Space Age, 85 Fed. Reg. at 52,424-25, 52,447 (identifying the agency's statutory basis and listing 47 U.S.C. §§ 151, 154(i), 301, 303, 307-310).

[^19]: Loper Bright Enters. v. Raimondo, 603 U.S. 369 (2024).

[^20]: Katherine T. McBrayer, Patrick R. Chai & Emily L. Judd, *Communication Delays, Disruptions, and Blackouts for Crewed Mars Missions*, at 2-8 (ASCEND 2022), https://ntrs.nasa.gov/citations/20220013418.

[^21]: Nat'l Aeronautics & Space Admin., Jet Propulsion Lab., *Remote Agent Experiment Meets All Objectives* (June 7, 1999), https://www.jpl.nasa.gov/news/remote-agent-experiment-meets-all-objectives/.

[^22]: Raymond Francis et al., *AEGIS Autonomous Targeting for ChemCam on Mars Science Laboratory: Deployment and Results of Initial Science Team Use*, 2 SCI. ROBOTICS eaan4582, abstract (2017).

[^23]: Raymond Francis et al., *AEGIS Autonomous Targeting for the SuperCam Instrument on the Mars 2020 Perseverance Rover*, at 3-5 (i-SAIRAS 2024), https://superintelligence.jpl.nasa.gov/public/documents/papers/francis-isairas-2024.pdf.

[^24]: NAT'L AERONAUTICS & SPACE ADMIN., SOFTWARE ENGINEERING REQUIREMENTS, NPR 7150.2D, preface P.2, §§ 3.6-3.7 (Mar. 8, 2022).

[^25]: 14 C.F.R. § 450.108(c), (e)-(f) (2024).

[^26]: Thomas Uriot et al., *Spacecraft Collision Avoidance Challenge: Design and Results of a Machine Learning Competition*, §§ 2-4, 7-8 (Oct. 12, 2020) (arXiv:2008.03069v2), https://arxiv.org/abs/2008.03069v2.

[^27]: *Id.* §§ 2, 4.

[^28]: Permanent Mission of China to the United Nations (Vienna), Note Verbale Dated 3 December 2021 Addressed to the Secretary-General, U.N. Doc. A/AC.105/1262 (Dec. 6, 2021); Permanent Mission of the United States of America to the United Nations (Vienna), Note Verbale Dated 28 January 2022 Addressed to the Secretary-General, U.N. Doc. A/AC.105/1265 (Jan. 28, 2022).

[^29]: Kyle Dunlap, David van Wijk & Kerianne L. Hobbs, *Run Time Assurance for Autonomous Spacecraft Inspection*, §§ 3, 4.2, 5 (Aug. 7, 2023) (arXiv:2302.02885v2), https://arxiv.org/abs/2302.02885v2.

[^30]: Convention on the International Regulations for Preventing Collisions at Sea rules 16-17, Oct. 20, 1972, 28 U.S.T. 3459, 1050 U.N.T.S. 16.

[^31]: GERMAN FEDERAL BUREAU OF AIRCRAFT ACCIDENTS INVESTIGATION, INVESTIGATION REPORT AX001-1-2/02 (May 2004).

[^32]: Guglielmo S. Aglietti et al., *RemoveDEBRIS: An In-Orbit Demonstration of Technologies for the Removal of Space Debris*, 124 AERONAUTICAL J. 1, §§ 3-7 (2020).

[^33]: Outer Space Treaty, *supra* note 7, arts. VI-IX.

[^34]: Ann N. Allen et al., *Bryde's Whales Produce Biotwang Calls, Which Occur Seasonally in Long-Term Acoustic Recordings from the Central and Western North Pacific*, 11 FRONTIERS MARINE SCI. art. 1394695, §§ 2-3 (2024).

[^35]: Peter Xiangyuan Ma et al., *A Deep-Learning Search for Technosignatures from 820 Nearby Stars*, 7 NAT. ASTRONOMY 492, §§ "Training Procedure," "Model Evaluation and Demonstration," "Search Results," "Discussion" (2023) (author manuscript), https://arxiv.org/abs/2301.12670v1.

[^36]: Sofia Z. Sheikh et al., *Analysis of the Breakthrough Listen Signal of Interest blc1 with a Technosignature Verification Framework*, 5 NAT. ASTRONOMY 1153, §§ 4-5 (2021) (author manuscript), https://arxiv.org/abs/2111.06350v1.

[^37]: Matt Lebofsky et al., *The Breakthrough Listen Search for Intelligent Life: Public Data, Formats, Reduction, and Archiving*, 131 PUBL'NS ASTRONOMICAL SOC'Y PAC. 124505, §§ I, II.1-II.3, III (2019) (author manuscript, Dec. 29, 2020), https://arxiv.org/abs/1906.07391v3.

[^38]: Int'l Acad. of Astronautics, SETI Permanent Study Grp., *Declaration of Principles Concerning the Conduct of the Search for Extraterrestrial Intelligence*, pmbl. & principles 1-5, 8 (Sept. 30, 2010), https://www.setileague.org/iaaseti/protocols_rev2010.pdf.

[^39]: N.Y. Times Co. v. United States, 403 U.S. 713, 714 (1971) (per curiam) (quoting Bantam Books, Inc. v. Sullivan, 372 U.S. 58, 70 (1963)).

[^40]: RESTATEMENT (THIRD) OF TORTS: LIABILITY FOR PHYSICAL AND EMOTIONAL HARM §§ 13(b), 16(a) (AM. L. INST. 2010).

[^41]: Mitigation of Orbital Debris in the New Space Age, 89 Fed. Reg. 13,276, 13,277-78 (Feb. 22, 2024) (order on reconsideration).

[^42]: LTS Guidelines, *supra* note 16, guideline A.2(2)(g)-(h), at 55.

[^43]: Samuel J. Rascoff & Richard L. Revesz, *The Biases of Risk Tradeoff Analysis: Towards Parity in Environmental and Health-and-Safety Regulation*, 69 U. CHI. L. REV. 1763 (2002).

[^44]: NAT'L AERONAUTICS & SPACE ADMIN., OVERVIEW OF THE DART MISHAP INVESTIGATION RESULTS 6 (2006), https://www.nasa.gov/pdf/148072main_DART_mishap_overview.pdf.
