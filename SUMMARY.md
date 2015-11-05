Summary
=======
* [1Introduction](introduction/README.md)
	* [1.1Use cases](introduction/use-case.md)
	* [1.2Relationship to other specifications](introduction/relationship-to-other-specifications.md)
	* [1.3Overview of this specification](introduction/overview-of-this-specification.md)
* [2Web Animations model overview](overview/README.md)
* [3Timing model](timing-model/README.md)
	* [3.1The timing model at a glance](timing-model/the-timing-model-at-a-glance.md)
		* [3.1.1Stateless](timing-model/stateless.md)
		* [3.1.2Hierarchical](timing-model/hierarchical.md)
    * [3.2Timing model concepts](timing-model/timing-model-concepts.md)
    * [3.3The global clock](timing-model/the-global-clock.md)
    * [3.4Timelines](timing-model/timelines.md)
        * [3.4.1Document timelines](timing-model/document-timelines.md)
        * [3.4.2The default document timeline](timing-model/the-default-document-timeline.md)
    * [3.5Animations](timing-model/animations.md)
        * [3.5.1Setting the timeline of a animation](timing-model/setting-the-timeline-of-a-animation.md)
        * [3.5.2Responding to a newly inactive timeline](timing-model/responding-to-a-newly-inactive-timeline.md)
        * [3.5.3Setting the target effect of an animation](timing-model/setting-the-target-effect-of-an-animation.md)
        * [3.5.4The current time of an animation](timing-model/the-current-time-of-an-animation.md)
        * [3.5.5Setting the current time of an animation](timing-model/setting-the-current-time-of-an-animation.md)
        * [3.5.6Setting the start time of an animation](timing-model/setting-the-start-time-of-an-animation.md)
        * [3.5.7Waiting for the target effect](timing-model/waiting-for-the-target-effect.md)
        * [3.5.8Promise objects](timing-model/promise-object.md)
        * [3.5.9The current ready promise](timing-model/the-current-ready-promise.md)
        * [3.5.10Playing an animation](timing-model/playing-an-animation.md)
        * [3.5.11Pausing an animation](timing-model/pausing-an-animation.md)
3.5.12Reaching the end
3.5.13The current finished promise
3.5.14Updating the finished state
3.5.15Finishing an animation
3.5.16Canceling an animation
3.5.17Speed control
3.5.17.1Updating the playback rate of an animation
3.5.18Reversing an animation
3.5.19Play states
3.5.20Animation events
3.5.20.1Types of animation events
3.5.20.2Event parameters
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
4.3.5.1Applying the composited result to a CSS property
4.3.5.2Applying the composited result to a DOM attribute
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