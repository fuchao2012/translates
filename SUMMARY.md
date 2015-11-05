Summary
=======
* [Introduction](introduction/README.md)
	* [Use cases](introduction/use-case.md)
	* [Relationship to other specifications](introduction/relationship-to-other-specifications.md)
	* [Overview of this specification](introduction/overview-of-this-specification.md)
* [Web Animations model overview](overview/README.md)
* [Timing model](timing-model/README.md)
	* [The timing model at a glance](timing-model/the-timing-model-at-a-glance.md)
		* [Stateless](timing-model/stateless.md)
		* [Hierarchical](timing-model/hierarchical.md)
    * [Timing model concepts](timing-model/timing-model-concepts.md)
    * [The global clock](timing-model/the-global-clock.md)
    * [Timelines](timing-model/timelines.md)
        * [Document timelines](timing-model/document-timelines.md)
        * [The default document timeline](timing-model/the-default-document-timeline.md)
    * [Animations](timing-model/animations.md)
        * [Setting the timeline of a animation](timing-model/setting-the-timeline-of-a-animation.md)
        * [Responding to a newly inactive timeline](timing-model/responding-to-a-newly-inactive-timeline.md)
        * [Setting the target effect of an animation](timing-model/setting-the-target-effect-of-an-animation.md)
        * [The current time of an animation](timing-model/the-current-time-of-an-animation.md)
        * [Setting the current time of an animation](timing-model/setting-the-current-time-of-an-animation.md)
        * [Setting the start time of an animation](timing-model/setting-the-start-time-of-an-animation.md)
        * [Waiting for the target effect](timing-model/waiting-for-the-target-effect.md)
        * [Promise objects](timing-model/promise-object.md)
        * [The current ready promise](timing-model/the-current-ready-promise.md)
        * [Playing an animation](timing-model/playing-an-animation.md)
        * [Pausing an animation](timing-model/pausing-an-animation.md)
        * [Reaching the end](timing-model/reaching-the-end.md)
        * [The current finished promise](timing-model/the-current-finished-promise.md)
        * [Updating the finished state](timing-model/updating-the-finished-state.md)
15Finishing an animation
16Canceling an animation
17Speed control
17.1Updating the playback rate of an animation
18Reversing an animation
19Play states
20Animation events
20.1Types of animation events
20.2Event parameters
3.6Animation effects
3.6.1Relationship between animation effects and animations
3.6.2Types of animation effects
3.6.3The active interval
3.6.4Local time
3.6.5Animation effect phases and states
3.7Fill behavior
3.7.1Fill modes
3.8Repeating
3.8.1Iteration intervals
3.8.2Controlling iteration
3.8.3Iteration time space
3.8.4Interval timing
3.9Core animation effect calculations
3.9.1Overview
3.9.2Calculating the active duration
3.9.3Transforming the local time
3.9.3.1Calculating the active time
3.9.3.2Calculating the scaled active time
3.9.3.3Calculating the iteration time
3.9.4Calculating the current iteration
3.10Direction control
3.10.1Calculating the directed time
3.11Time transformations
3.11.1Scaling the time
3.11.2Timing functions
3.11.3Scaling using a cubic Bézier curve
3.11.4Timing in discrete steps
3.11.5Calculating the transformed time
3.11.6Calculating the iteration progress
4Animation Model
4.1Keyframe effects
4.1.1Target properties
4.1.2Procedures for animating properties
4.1.3Specific animation behaviors
4.1.3.1Not animatable
4.1.3.2Animatable as string
4.1.3.3Animatable as real number
4.1.3.4Animatable as length, percentage, or calc
4.1.3.5Animatable as color
4.1.3.6Animatable as transform list
4.1.3.7Other animation behaviors
4.1.4Effect values
4.2Keyframes
4.2.1Spacing keyframes
4.2.1.1Applying spacing to keyframes
4.2.2The effect value of a keyframe effect
4.3Combining effects
4.3.1Animation types
4.3.2The effect stack
4.3.3Calculating the result of an effect stack
4.3.4Effect composition
4.3.5Applying the composited result
4.1Applying the composited result to a CSS property
4.2Applying the composited result to a DOM attribute
4.3.6Effect accumulation
5Programming interface
5.1 Time values in the programming interface
5.2The AnimationTimeline interface
5.3The DocumentTimeline interface
5.4The Animation interface
5.4.1The AnimationPlayState enumeration
5.5The AnimationEffectReadOnly interface
5.6The AnimationEffectTimingReadOnly interface
5.7The AnimationEffectTiming interface
5.8The AnimationEffectTimingProperties dictionary
5.9The ComputedTimingProperties dictionary
5.9.1The FillMode enumeration
5.9.2The PlaybackDirection enumeration
5.10The KeyframeEffectReadOnly and KeyframeEffect interfaces
5.10.1Creating a new KeyframeEffect object
5.10.2Property names and IDL names
5.10.3Processing a frames argument
5.10.4The KeyframeEffectOptions dictionary
5.10.5Computed keyframes
5.11The IterationCompositeOperation enumeration
5.12The CompositeOperation enumeration
5.13The SharedKeyframeList interface
5.14The Animatable interface
5.15Extensions to the Document interface
5.16Extensions to the Element interface
5.17Extensions to the PseudoElement interface
5.18The AnimationPlaybackEvent interface
5.19Model liveness
6Integration with Media Fragments
7Interaction with page display
8Implementation requirements
8.1Precision of time values
8.2Conformance criteria
9Acknowledgements
10Changes since last publication
Conformance
Document conventions
Index
Terms defined by this specification
Terms defined by reference
References
Normative References
Informative References
IDL Index
Issues Index
