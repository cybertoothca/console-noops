# console-noops
A simple Javascript library that will prevent legacy browsers from throwing
errors when they don't support basic console functions.

Here is a list of the console functions that are muted in those legacy browsers:

    console.assert(...);
    console.clear(...);
    console.count(...);
    console.debug(...)
    console.dir(...);
    console.dirxml(...);
    console.error(...);
    console.exception(...);
    console.group(...);
    console.groupCollapsed(...);
    console.groupEnd(...);
    console.info(...);
    console.log(...);
    console.markTimeline(...);
    console.profile(...);
    console.profileEnd(...);
    console.table(...);
    console.time(...);
    console.timeEnd(...);
    console.timeStamp(...);
    console.trace(...);
    console.warn(...);

## Thank You

[This solution was proposed over here in stackoverflow](http://stackoverflow.com/a/16916941/545137)
