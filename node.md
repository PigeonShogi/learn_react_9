const [state, dispatchFn] = useReducer(reducerFn, initialState, initFn)

reducerFn
(prevState, action) => newState