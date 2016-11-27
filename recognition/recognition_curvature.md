### Heirarchy of Composition

When thinking about an object, not all details are present.  Just the essentials.

1. For example, ask someone to draw a crowd:  You will get a bunch of stick people.  With just heads in the back rows.
1. Ask someone to draw a person: You may get a stick person with the addition of a shirt and pants and smiley face.
1. Ask them to draw a face: ears, nose, and hair may be added to the face.
1. Ask them to draw an eye: probably recieving a football outline with a black circle inset.


### Curvature Recognition Idea #1

Render the image using a edge detection, so we only draw the edges.

The point at which we are looking, draw a circle.  Expand the circle
to encompass the entire image.  When edges from the environment cross
the circle, this makes a point.  The motion of these points is what 
we register and is what we use to remember and recognize like-objects.

For example: A picture frame is a square. All squares viewed by this method
will appear as one point that splits into two, which diverge then comes back
at a steady rate.

Note that this happens for every frame. 

There are other versions that may work as well:
1. don't use a circle, but use eye movement. 
1. Or, start a point at the closest corner of the object
to the center of our field of view (or field of focus)
and draw a circle that grows bigger.   Where it crosses
the edges of the object place points.  Track the points movement.

* A 3D version of this should probably run simultaneously.





