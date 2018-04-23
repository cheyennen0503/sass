# Entry 4: Fast Learning
For this week, I had to pick up the pace with my learning. I finished up the last three sections of learning SASS codecademy.

## Mixins and the "&" Selector 
When I first started reading about mixins in the SASS documentation, I did not understand how they worked the power of what they could do. When I saw it utilized for the first time in codecademy, I realized that mixins can be very helpful for keeping my code DRY. They can take in arguments, assign default values, and accepts arguments in any order. 
Mixins look like this:
```
@mixin backface-visibility {
  backface-visibility: hidden;
  -webkit-backface-visibility: hidden;
  -moz-backface-visibility: hidden;
  -ms-backface-visibility: hidden;
  -o-backface-visibility: hidden;
}
```
And are used like this:

```
.notecard {
.front, .back {
    width: 100%;
    height: 100%;
    position: absolute;

    @include backface-visibility;
  }
}
```

## Next Steps
1. Watch the Youtube Video. Since I was so focused on codecademy this week, watching this video I hope will help me get an even better understanding of SASS.
2. Build small things with what I have learned in SASS so far. 
3. Start planning what it is that I want to do for my project towards the end of the week. 

## Takeaways
+ Ask the people around you for help. Learning something new on your own is hard. Independent study does not mean you have to always be independent. You can learn a lot from others especially ones who are doing the same topic as you because you might not be learning the same way.
+ Take your time when you are trying to understand something. If you do not get something the first time, break it down into smaller ideas. Make connections with what you hae previously learned. Use google. 








[Previous](../entries/entry03.md) |  Next

[Table of Contents](../README.md)