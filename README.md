<div align="center">
  <h1 align="center">
    ↩ react-hook
  </h1>
  <h3>
    Reusable React hooks for function components
  </h3>
  <br>
  <br>
</div>

| Hook                                                          | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| ------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [`useAsync()`](packages/async)                                | A React hook for gracefully resolving, cancelling, and handling errors for async functions and promises.                                                                                                                                                                                                                                                                                                                                                        |
| [`useCache()`](packages/cache)                                | A React hook for accessing an asynchronous key/value cache that persists data between renders and components. This allows you to do neat stuff like preload data before your next page or component has even started mounting.                                                                                                                                                                                                                                  |
| [`useChange()`](packages/change)                              | A React hook that invokes a callback anytime a value changes                                                                                                                                                                                                                                                                                                                                                                                                    |
| [`useClick()`](packages/click)                                | A React hook for conditionally firing a function when an element is clicked - for instance if you only want a click even to fire on double-clicks.                                                                                                                                                                                                                                                                                                              |
| [`useCopy()`](packages/copy)                                  | A React hook for copying text to the clipboard                                                                                                                                                                                                                                                                                                                                                                                                                  |
| [`useCounter()`](packages/counter)                            | A React hook counter with min/max/step/cast options                                                                                                                                                                                                                                                                                                                                                                                                             |
| [`useDebounce()`](packages/debounce)                          | A React hook for debouncing setState and other callbacks                                                                                                                                                                                                                                                                                                                                                                                                        |
| [`useEvent()`](packages/event)                                | A React hook for adding events to HTML elements. This hook cleans up your listeners automatically when it unmounts. You won't have to worry about wrapping your listener in a `useCallback()` because this hook makes sure your most recent callback is always invoked.                                                                                                                                                                                         |
| [`useGoogleOptimize()`](packages/google-optimize)             | A React hook for adding Google Optimize variants to components.                                                                                                                                                                                                                                                                                                                                                                                                 |
| [`useHotkey()`](packages/hotkey)                              | A React hook for invoking a callback when hotkeys are pressed. This hook also provides interop between `event.key` and `event.which` - you provide a string, and the library turns it into an `event.which` key code if it has to.                                                                                                                                                                                                                              |
| [`useHover()`](packages/hover)                                | A React hook for tracking the hover state of DOM elements in browsers where hovering is possible. If the browser does not support hover states (e.g. a phone) the `isHovering` value will always be `false`.                                                                                                                                                                                                                                                    |
| [`useIntersectionObserver()`](packages/intersection-observer) | A React hook for the IntersectionObserver API that uses a polyfill when the native API is not available.                                                                                                                                                                                                                                                                                                                                                        |
| [`useLatest()`](packages/latest)                              | A React hook that updates useRef().current with the most recent value each invocation                                                                                                                                                                                                                                                                                                                                                                           |
| [`useMediaQuery()`](packages/media-query)                     | React hooks that update when media queries change between matched and unmatched states.                                                                                                                                                                                                                                                                                                                                                                         |
| [`useMergedRef()`](packages/merged-ref)                       | A React hook for merging multiple refs into one ref.                                                                                                                                                                                                                                                                                                                                                                                                            |
| [`useMousePosition()`](packages/mouse-position)               | A React hook for tracking the position, hover, and "down" state of the mouse as it interacts with an element. This hook provides interoperability between touch and desktop devices and will treat `ontouch` events the same as `onmouse` ones. Additionally, this hook is throttled to `30fps` by default using a [useThrottle() hook](https://github.com/jaredLunde/react-hook/tree/master/packages/throttle), though the precise frame rate is configurable. |
| [`usePassiveLayoutEffect()`](packages/passive-layout-effect)  | A React hook that uses `useEffect()` on the server and `useLayoutEffect()` in the browser                                                                                                                                                                                                                                                                                                                                                                       |
| [`usePrevious()`](packages/previous)                          | A React hook that stores a value from the previous render                                                                                                                                                                                                                                                                                                                                                                                                       |
| [`useResizeObserver()`](packages/resize-observer)             | A React hook that fires a callback whenever `ResizeObserver` detects a change to its size.                                                                                                                                                                                                                                                                                                                                                                      |
| [`useServerPromises()`](packages/server-promises)             | A React hook for continuously rendering a React tree until no promises are pushed to `server-promises`'s context in a given render                                                                                                                                                                                                                                                                                                                              |
| [`useSize()`](packages/size)                                  | A React hook for measuring the size of HTML elements including when they change                                                                                                                                                                                                                                                                                                                                                                                 |
| [`useSwitch()`](packages/switch)                              | A React hook for controlling a boolean value with toggle, on, and off callbacks.                                                                                                                                                                                                                                                                                                                                                                                |
| [`useThrottle()`](packages/throttle)                          | A React hook for throttling setState and other callbacks.                                                                                                                                                                                                                                                                                                                                                                                                       |
| [`useToggle()`](packages/toggle)                              | A React hook for toggling between two values with a callback.                                                                                                                                                                                                                                                                                                                                                                                                   |
| [`useWindowScroll()`](packages/window-scroll)                 | A React hook for updating components when the scroll position of the window on the y-axis changes.                                                                                                                                                                                                                                                                                                                                                              |
| [`useWindowSize()`](packages/window-size)                     | React hooks for updating components when the size of the `window` changes.                                                                                                                                                                                                                                                                                                                                                                                      |

## Contributing

[👋Click here to see **how to contribute**](./CONTRIBUTING.md)

## LICENSE

MIT
