# Data Collection Quality Checklist

> **Portfolio Demonstration**
>
> A practical checklist for reviewing first-person and multimodal AI training data before submission. This checklist is intended as a general quality-control framework and does not reproduce confidential client or platform instructions.

## Purpose

High-quality AI datasets require more than successful recording or data capture. Each sample should be reviewed to ensure that it is clear, complete, consistent, and suitable for the intended AI task.

This checklist provides a structured review process for egocentric video and multimodal data.

---

## 1. Recording Setup

Before recording:

* [ ] Camera or recording device is securely mounted
* [ ] First-person viewpoint is appropriate for the activity
* [ ] Recording environment is suitable
* [ ] Main workspace is visible
* [ ] Required objects are available
* [ ] Lighting is sufficient
* [ ] Unnecessary background distractions are minimized
* [ ] Recording device has sufficient battery and storage

---

## 2. Viewpoint Quality

The recording should provide a useful representation of the participant's perspective.

* [ ] First-person viewpoint remains consistent
* [ ] Camera position supports understanding of the activity
* [ ] Important hand movements are visible when relevant
* [ ] Important objects remain within the field of view
* [ ] Camera orientation does not unexpectedly change
* [ ] The viewpoint does not make important actions impossible to interpret

**Quality standard:** The viewer should be able to understand the activity from the recorded perspective without unnecessary ambiguity.

---

## 3. Framing

Check whether important content remains visible throughout the activity.

* [ ] Main workspace is visible
* [ ] Primary objects are not consistently cut off
* [ ] Important interactions occur within the frame
* [ ] The camera is not pointed excessively toward irrelevant areas
* [ ] Temporary framing changes do not hide critical actions

### Common Problems

**Major:** The main activity is mostly outside the frame.

**Moderate:** Important interactions are partially hidden.

**Minor:** Small framing inconsistencies occur without affecting interpretation.

---

## 4. Lighting and Visibility

The recording should contain sufficient visual information.

* [ ] Main objects are clearly visible
* [ ] Hands can be distinguished from the environment
* [ ] Shadows do not consistently hide important actions
* [ ] Excessive glare is avoided
* [ ] Extremely dark areas do not contain critical actions
* [ ] Exposure remains reasonably consistent

**Quality standard:** A reviewer should be able to identify the important objects and actions without excessive difficulty.

---

## 5. Camera Stability

Natural movement is expected in egocentric recordings, but excessive movement can reduce data usability.

* [ ] Camera remains securely mounted
* [ ] Movement remains reasonably natural
* [ ] Excessive shaking is absent
* [ ] Important actions remain interpretable during movement
* [ ] Sudden camera movements do not repeatedly obscure the activity

### Severity Guide

**Major:** Severe movement makes the activity difficult or impossible to understand.

**Moderate:** Noticeable movement interferes with portions of the activity.

**Minor:** Small or natural movement has little effect on interpretation.

---

## 6. Activity Completeness

Confirm that the recording captures the meaningful progression of the activity.

* [ ] Activity begins at an appropriate point
* [ ] Important preparation actions are captured
* [ ] Main actions are visible
* [ ] Important object interactions are captured
* [ ] Intermediate steps are not unnecessarily missing
* [ ] Activity reaches a recognizable conclusion

### Key Question

**Can another person understand what happened from the beginning of the recording to the end?**

If the answer is no, investigate whether missing actions or poor visibility are responsible.

---

## 7. Object Interaction

For activities involving physical objects:

* [ ] Relevant objects can be identified
* [ ] Objects are visible during important interactions
* [ ] Picking up and placing objects can be interpreted
* [ ] Object-to-object interactions are visible
* [ ] Important object movements are not completely obstructed
* [ ] The sequence of interactions remains understandable

Examples include:

* Picking up a cup
* Opening a container
* Pouring a liquid
* Folding clothing
* Washing an object
* Moving items between locations
* Using a household tool

---

## 8. Temporal Consistency

The recording should maintain logical continuity.

* [ ] Actions occur in a coherent sequence
* [ ] Objects do not unexpectedly appear or disappear
* [ ] The environment remains reasonably consistent
* [ ] There are no unexplained jumps in the activity
* [ ] Important transitions are understandable
* [ ] The recording does not contain unexplained interruptions

**Quality standard:** Events should appear to happen naturally and in a logical order.

---

## 9. Audio Quality

When audio is part of the dataset:

* [ ] Relevant speech can be understood
* [ ] Important sounds are not excessively distorted
* [ ] Background noise does not consistently overwhelm relevant audio
* [ ] Audio remains reasonably synchronized with the video
* [ ] Unexpected interruptions are identified

If audio is not required for the task, its absence should not automatically be treated as a quality issue.

---

## 10. Environmental Quality

Review the surrounding environment.

* [ ] Recording takes place in an appropriate environment
* [ ] Important areas are reasonably clean and visible
* [ ] Unnecessary distractions are minimized
* [ ] Objects relevant to the task are distinguishable
* [ ] Environmental changes do not create unexplained inconsistencies

The environment does not need to be perfectly controlled. The priority is whether it affects the usefulness of the data.

---

## 11. Privacy and Sensitive Information

Before submitting a recording:

* [ ] Unnecessary personal information is not visible
* [ ] Sensitive documents are not unintentionally captured
* [ ] Private screens or information are not unnecessarily exposed
* [ ] Other people are not unintentionally included where avoidable
* [ ] Recording complies with the applicable project requirements

**Important:** Privacy requirements should always take priority over convenience during data collection.

---

## 12. Final Quality Review

After recording, conduct a complete review rather than checking only individual frames.

### Review Questions

**Perspective**

* Is the intended viewpoint maintained?

**Visibility**

* Can the important objects and actions be seen?

**Completeness**

* Is the activity captured from beginning to end?

**Continuity**

* Does the activity progress logically?

**Stability**

* Does camera movement interfere with interpretation?

**Environment**

* Does the environment introduce significant distractions?

**Privacy**

* Is unnecessary sensitive information visible?

**Usability**

* Could another reviewer or AI system reasonably interpret the recorded activity?

---

## 13. Severity Classification

### Major Issue

A major issue significantly compromises the usefulness of the sample.

Examples:

* Main activity is not captured
* Critical actions are completely missing
* Severe obstruction prevents interpretation
* Recording is unusable for the intended task
* Significant privacy issue is present

### Moderate Issue

A moderate issue reduces quality but the sample remains potentially usable.

Examples:

* Several actions are partially obscured
* Camera movement affects part of the recording
* Lighting temporarily reduces visibility
* Important transitions are difficult to interpret

### Minor Issue

A minor issue has limited impact on the dataset.

Examples:

* Brief natural camera movement
* Small framing inconsistency
* Temporary background distraction
* Short partial obstruction that does not hide a critical action

---

## 14. Final Decision

After completing the checklist, classify the sample using one of three outcomes:

### Suitable

The recording satisfies the required quality criteria and contains sufficient information for its intended purpose.

### Review Required

The recording contains identifiable issues that should be assessed before final submission.

### Unsuitable

The recording contains major problems that prevent reliable use for the intended dataset.

---

## 15. Quick Pre-Submission Checklist

Before submitting any sample, confirm:

* [ ] Correct viewpoint
* [ ] Clear framing
* [ ] Adequate lighting
* [ ] Reasonable stability
* [ ] Complete activity
* [ ] Visible object interactions
* [ ] Logical temporal sequence
* [ ] Acceptable environment
* [ ] Appropriate audio where required
* [ ] No unnecessary sensitive information
* [ ] Final playback completed
* [ ] Any identified issues documented

---

## Quality-Control Principle

The goal of data collection is not simply to produce a recording.

The goal is to produce **usable data**.

A successful sample should provide enough clear, consistent, and complete information for the intended AI system, dataset reviewer, or downstream annotation process to understand the captured activity.

## Skills Demonstrated

This checklist demonstrates:

* Multimodal data quality control
* Egocentric video review
* Recording validation
* Visual inspection
* Activity completeness assessment
* Object-interaction verification
* Temporal consistency checking
* Error classification
* Evidence-based quality decisions
* Pre-submission dataset review

## Portfolio Note

This checklist is a general portfolio framework created for demonstration purposes. It does not contain confidential client information, proprietary project instructions, or restricted platform procedures.
