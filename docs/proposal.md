# The proposal as a working instrument

Part VII of the Article proposes a **task-specific authorization record**, backed by independent scrutiny and by
event records. This page sets the proposal out as a template that an operator or a regulator can fill in. Every
field comes from the Article's text. Which institution can lawfully require the record is the question of Part
VII.D.

## 1. The two-threshold screen

The screen comes before the record. A record cannot cure a failure at either threshold.

| Question | Answer and basis |
| --- | --- |
| **Threshold 1: authority.** Does the actor have authority to undertake this activity and impose the exposure it creates? Cite the license, consent or other legal basis, for example registry-state consent for capture. | |
| **Threshold 2: evidence.** Does the evidence justify delegating *this class of action* under *these conditions*? Cite the flight, test or analytical evidence and its scope. | |
| **Timing.** Can individual review still change the outcome: before practical irreversibility, with information that can expose a material error, by someone competent and authorized to act on it? | |
| **Choice.** Individual approval, advance-constrained action, a justified fallback, or no permission. | |

Each line has a counterpart in the law of delegation.

| Element | What the law of delegation asks of a human delegate | Authority |
| --- | --- | --- |
| Threshold 1 | A private actor may not be given power over its rivals | *Carter v. Carter Coal Co.*, 298 U.S. 238 (1936) |
| Threshold 2 | A delegation is justified on a record that examines the relevant data and the obvious alternatives | *Motor Vehicle Mfrs. Ass'n of the U.S., Inc. v. State Farm Mut. Auto. Ins. Co.*, 463 U.S. 29 (1983) |
| Timing | A retained final decision that cannot be exercised in time is no retention | *U.S. Telecom Ass'n v. FCC*, 359 F.3d 554 (D.C. Cir. 2004) |

## 2. The authorization record

| Field | What it states |
| --- | --- |
| Responsible actor | The operator, the named supervisor, and the authorizing state or institution |
| Action class | The defined class of actions permitted without contemporaneous approval, for example target selection within parameters, or maneuver policies of listed types |
| Operating conditions | The data-quality, state-estimation, coordination and trajectory conditions under which the permission holds |
| Forbidden effects and resource limits | What the action must never do; propellant, power and pointing limits |
| Exposed interests | Whose assets, services or interests the action can affect, including other operators, service users and later entrants |
| Feasible alternatives considered | Ground-planned sequences, onboard crew, conventional protective controllers, constrained planners, and why each is insufficient |
| Fallback when the authorization no longer fits | The behavior when conditions fail, justified by the mission's dynamics. Passivity is not automatically safe, and the fallback's risks are compared with those of continuing, as 14 C.F.R. § 450.108 does for flight abort |
| Reassessment triggers | Software changes that affect permitted behavior, materially different environments, evidence that data assumptions no longer hold, expansion of action types, new objectives or information sources |
| Routine maintenance | Changes that leave the justification intact and need no reassessment |
| Independent scrutiny | Who reviewed the baseline and the excluded scenarios, and with what independence |
| Coordination | The right-of-way rule the policy follows and the maneuver-intent messages it sends, stated before any particular prediction model is required |
| Disclosure | Public justification of the action class, the protected interests and the reasons; controlled access to sensitive detail |

**Evidentiary burdens.** The applicant shows why existing arrangements are insufficient and what the capability can
and cannot do. The regulator justifies its conditions and explains why lighter precautions are inadequate, and it
enters the benefits of approval, certification and disclosure in the same ledger as their delay and expense.
Serious external effects without a credible basis for the operating range justify refusal or postponement.

## 3. The record applied to the Article's four activities

| Activity | Authorized in advance | Reserved for fresh review |
| --- | --- | --- |
| Instrument targeting, as in AEGIS | Selection within parameters set by scientists, with independent protections against unsafe pointing | Changes to scientific goals or to hazardous operating conditions |
| Collision avoidance | A set of maneuver policies with data-quality, coordination and trajectory constraints | Expanding maneuver types, changing the objective, relying on a new information source |
| Debris capture | Execution limits and automatic abort or separation within an approved plan | Target identity and legal permissions, resolved before close approach |
| SETI, as an institutional analog | Candidate generation and circulation with explicit candidate status | Confirmation claims and any deliberate response |

**Proximity operations, in the Article's example.** The record names the responsible operator supervisor. When
validated state-estimation conditions fail, the onboard system inhibits further approach and executes a separately
tested contingency suited to the geometry. It preserves the event record and notifies the supervisor at the next
contact. Resumption requires documented restoration of the conditions, and a material expansion of the operating
range returns to the authorizing institution. Inhibiting the operation is an engineering action and leaves the
legal authority where it was.

## 4. The event record

Kept so that consequential decisions can be reconstructed:

```text
observations and their uncertainty
software and policy versions in force
permitted action range at the time
selected action and its inputs
human interventions (who, when, what)
information exchanged with other actors
```

Retention reflects the activity, the needs of investigation, claim periods, storage, and privacy or security
interests. For SETI, preserving the underlying observations matters more than a model's prose explanation. An
explanation produced after the event carries weight only when it can be tied to the process that produced the
action.

## 5. The record's legal effect

- **Evidence of fault and of care.** A documented operating range supplies the account of available precautions
  that the Liability Convention's fault standard requires. Departure from the range is evidence of fault, in the
  way a violated safety standard is evidence of negligence. Operation within it is evidence of care without being a
  defense, as compliance with a statute is in the common law of torts.
- **Authority.** The record implements authority the actor already holds. It does not extend that authority, and
  it confers no immunity.
- **Private contracts.** Supplier contracts allocate audit access and recourse among private parties and leave the
  treaty obligations of launching states as they are.
- **Institution.** A condition on autonomous maneuvering is tested against the text of the agency's statute by a
  court exercising independent judgment, so where existing authority cannot sustain the condition the proposal
  calls for legislation or another competent institution.
