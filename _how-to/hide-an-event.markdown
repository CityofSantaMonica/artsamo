# How to hide an event page

While [editing[(https://github.com/CityofSantaMonica/artsamo/blob/master/_how-to/make-changes.markdown) an event file, look for the `featured` line:
```yml
title: Meet me at Reed
featured: true
```

(If you don’t see the `featured` line, you can add it.)

To hide the event, set the value of featured to `false`:
```yml
title: Meet me at Reed
featured: false
```

To show the event again, set the value of featured to `true`.
```yml
title: Meet me at Reed
featured: true
```
