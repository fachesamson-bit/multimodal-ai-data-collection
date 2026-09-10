# Egocentric Video Data Collection Case Study

> **Synthetic Example / Portfolio Demonstration**
>
> This case study demonstrates a structured approach to collecting and quality-checking first-person (egocentric) video data for AI training. It uses a synthetic household activity and does not contain confidential client, platform, or proprietary task data.

## Objective

The objective is to capture a natural household activity from a first-person point of view while maintaining sufficient visual quality, activity completeness, stable framing, and clear object interactions.

The collected video should allow an AI system to understand:

* What activity is being performed
* Which objects are being handled
* The sequence of actions
* How objects interact with one another
* The surrounding environment
* The progression of the activity from beginning to completion

## Example Activity

**Activity:** Preparing a simple beverage

**Recording perspective:** Head-mounted first-person POV

**Environment:** Clean and well-lit kitchen area

**Primary objects:**

* Cup
* Water bottle
* Spoon
* Beverage container
* Kitchen counter

## Recording Setup

The recording is performed from the participant's natural first-person perspective using a head-mounted smartphone.

Before recording, the environment is checked to ensure that:

* The main working area is visible
* Important objects are within the camera's field of view
* Lighting is sufficient
* The camera is securely mounted
* The recording area is free from unnecessary obstructions
* The full activity can be completed naturally

## Collection Plan

The activity is divided into logical stages rather than treating the recording as a collection of isolated actions.

### Stage 1 — Preparation

The participant approaches the workspace and confirms that the required objects are available.

### Stage 2 — Object Interaction

The participant picks up the cup and beverage container and positions them on the working surface.

### Stage 3 — Preparation

The beverage is prepared through a natural sequence of actions such as opening the container, adding the required contents, and introducing water.

### Stage 4 — Mixing

A spoon is used to mix the contents inside the cup.

### Stage 5 — Completion

The completed beverage is placed on the counter and the activity ends.

## Expected Action Sequence

A successful recording should preserve the logical progression of the activity:

1. Approach the workspace
2. Locate the required objects
3. Pick up the cup
4. Place the cup on the counter
5. Pick up the beverage container
6. Add the beverage contents
7. Add water
8. Pick up the spoon
9. Mix the contents
10. Place the completed beverage on the counter
11. End the recording

The exact sequence may vary naturally depending on the activity, but the recording should remain understandable from beginning to end.

## Data-Quality Checks

After recording, the video is reviewed for several quality dimensions.

### 1. Viewpoint

The camera should maintain a natural first-person perspective throughout the activity.

**Check:**

* Hands and relevant objects are visible when possible
* The camera remains aligned with the participant's actions
* The viewpoint does not unexpectedly change

### 2. Framing

Important actions and objects should remain sufficiently visible.

**Check:**

* Objects are not consistently cut off
* The primary workspace remains visible
* Important interactions occur within the camera frame

### 3. Lighting

The scene should contain enough light to distinguish objects and actions.

**Check:**

* Objects can be identified clearly
* Excessive darkness is avoided
* Strong glare does not obscure important actions

### 4. Stability

Head movement should remain natural without making the recording difficult to interpret.

**Check:**

* No excessive shaking
* No unnecessary camera movement
* Actions remain visually understandable

### 5. Activity Completeness

The recording should capture the meaningful stages of the activity.

**Check:**

* The activity begins before the main action
* Important intermediate actions are captured
* The activity reaches a clear conclusion

### 6. Object Visibility

Objects involved in the activity should remain identifiable.

**Check:**

* Cup remains visible during important interactions
* Beverage container is visible when contents are added
* Spoon is visible during mixing
* Important object interactions are not completely obstructed

## Example Quality-Control Findings

| Quality Area          | Observation                                                               | Severity |
| --------------------- | ------------------------------------------------------------------------- | -------- |
| Viewpoint             | First-person perspective remains consistent throughout the recording      | Pass     |
| Framing               | Main workspace remains visible during most actions                        | Pass     |
| Lighting              | Objects remain clearly distinguishable                                    | Pass     |
| Stability             | Minor natural head movement is present but does not affect interpretation | Minor    |
| Activity Completeness | Preparation, mixing, and completion are captured                          | Pass     |
| Object Visibility     | Main objects remain identifiable during interactions                      | Pass     |

## Potential Issues and Severity

### Major

A major issue would significantly reduce the usefulness of the recording.

Examples:

* The main activity is largely outside the camera frame
* Important actions are completely missing
* Severe obstruction prevents identification of key objects
* The recording ends before the main task is completed

### Moderate

A moderate issue affects quality but does not make the recording unusable.

Examples:

* Several important actions are partially obstructed
* Temporary poor framing makes an interaction difficult to interpret
* Noticeable camera movement affects a short portion of the recording
* Lighting temporarily makes an object difficult to identify

### Minor

A minor issue has limited impact on interpretation.

Examples:

* Brief natural head movement
* Small framing inconsistencies
* Temporary background distraction
* Short periods where an object is partially obscured

## Validation Process

The final review follows a simple validation sequence:

**1. Verify the recording perspective**

Confirm that the video represents the intended first-person viewpoint.

**2. Verify activity coverage**

Confirm that the meaningful stages of the activity are present.

**3. Verify object interactions**

Confirm that important objects can be identified and their interactions understood.

**4. Verify visual quality**

Check framing, lighting, stability, and visibility.

**5. Verify consistency**

Ensure that the recording remains coherent from beginning to end.

**6. Determine final quality**

Classify the recording as suitable, requiring review, or unsuitable based on the observed issues.

## Example Validation Outcome

**Result: Suitable for dataset review**

The synthetic recording successfully captures the activity from a first-person perspective. The primary objects remain identifiable, the major actions are represented, and the activity progresses logically from preparation to completion.

A small amount of natural head movement is present, but it does not prevent interpretation of the activity.

## Lessons Learned

Effective egocentric data collection requires more than simply recording an activity.

The quality of the resulting dataset depends on:

* Planning the activity before recording
* Maintaining a useful first-person viewpoint
* Keeping important interactions within the frame
* Ensuring sufficient lighting
* Capturing the complete activity
* Reviewing the recording before submission
* Identifying quality issues objectively rather than assuming the recording is acceptable

The most important principle is **data usability**: the final recording should contain enough clear visual information for an AI system or human reviewer to understand what happened.

## Skills Demonstrated

This case study demonstrates:

* Egocentric video data collection
* First-person POV recording
* Activity planning
* Object-interaction capture
* Visual quality assessment
* Data-quality control
* Completeness checking
* Structured validation
* Error identification
* Evidence-based quality assessment

## Professional Application

This workflow is relevant to AI training datasets involving:

* Human activity recognition
* Computer vision
* Multimodal AI
* Robotics
* Object interaction understanding
* Embodied AI
* Video-language models
* Human behavior understanding

## Portfolio Note

This is a synthetic portfolio demonstration created to illustrate data-collection and quality-control methodology.

It does not reproduce confidential client instructions, private datasets, proprietary platform workflows, or restricted project information.
