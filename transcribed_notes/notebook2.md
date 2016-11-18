How do you recognize an object?
===============================

It, or one if its sub-components, resembles a previously viewed
and stored form(shape), texture, or movement (change in shape over time).

As previously stated, effects are applied to the possible remembered objects
to justify which is the most probable match.

****************

### How do you identify objects that share effects?

* Effects that are observed and stored, are categorized 
so similar effects can be recalled.
* Each effect has a collection of associated objects.
* Objects are also stored in proximity to each other by similarity.
* If grouped (similar) effects are associated with objects that 
are similar* then this similarity is a theory for the effect.
* Other objects with this similarity are then assumed to share the effect.
* (Simply find the characteristics that match best between the objects)

*Side Note: I think the main piece I was missing when I wrote this
was that the objects could be distilled into a composition of feelings,
**before** performing these comparisons.  Which makes everything above
much easier to code.*

**************
Matrix Associated Distance
**************

### Phase I

    This is phase 1 of object recognition: The proximity phase.

**objects**:*asymmetrical, bulbous, clean rough, wet, forked, curvy,
brightness, hue, saturation, soft, heavy, large, spindly, motion (*expand this one*)

*many properties represent both extremes, for example: symmetrical=-1.0
***************

### Phase II

Composition of primary shapes are used to Identify objects.
This can be arbitrarily more accurate as we grow familiar
with the object.  __This is what we draw.__

For example, a computer charger is made of 5 parts:
1. electrical plug (to outlet)
2. electrical cord
3. black box (transformer)
4. more cord
5. connector (to PC)

These are shapes.  They may be references to other objects.
****************

### Phase III

**Final Hash**

Use a more "traditional" hash algorithm.

>"Can't tell what is different, but I do not recognize that as my phone charger."

Could be the position of text on the label, or the subtle curves at the corners, etc.
This may simply be the exact values of **Phase I** all hashed together.

(As I transcribe this, I would agree with that last sentence)