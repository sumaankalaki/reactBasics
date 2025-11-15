
1.How to creat react using vite and reactDom

/------------------------------------------------------
[4th video] ABOUT HOOKS
/------------------------------------------------------
1️⃣ useState
Used to add and manage state in functional components.
const [count, setCount] = useState(0);
2️⃣ useEffect
Used for side effects like fetching data, timers, event listeners.
useEffect(() => { ... }, []);
3️⃣ useContext
Used to consume values from React Context without prop drilling.
const user = useContext(UserContext);

| Category       | Hooks                                                                                         |
| -------------- | --------------------------------------------------------------------------------------------- |
| **Basic**      | useState, useEffect, useContext                                                               |
| **Additional** | useRef, useMemo, useCallback, useReducer, useLayoutEffect, useImperativeHandle, useDebugValue |
| **Advanced**   | useTransition, useDeferredValue, useId, useSyncExternalStore, useInsertionEffect              |
| **Custom**     | Your own hooks (e.g., useFetch, useTimer)                                                     |

⭐ 2. Additional Hooks
4️⃣ useRef
Used to access DOM elements or store mutable values.
const inputRef = useRef();
5️⃣ useReducer
Alternative to useState for complex state logic.
const [state, dispatch] = useReducer(reducer, initialState);
6️⃣ useCallback
Used to memoize functions to prevent unnecessary re-renders
const handleClick = useCallback(() => {}, []);
7️⃣ useMemo
Used to memoize expensive computations.
const result = useMemo(() => computeValue(a, b), [a, b]);
8️⃣ useLayoutEffect
Similar to useEffect but runs before the browser paints the screen.
Used for measurements, DOM updates.
9️⃣ useImperativeHandle
Customizes the value exposed when using ref on parent components.
🔟 useDebugValue
Used to display custom labels in React DevTools—mainly for custom hooks.
1️⃣1️⃣ useDeferredValue
Used to defer value transitions for smoother UI performance.
1️⃣2️⃣ useTransition
Used to mark state updates as “transition” for better performance.
1️⃣3️⃣ useId
Generates unique IDs in SSR-friendly way (for forms, accessibility).

