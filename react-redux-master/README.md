After completing this lab, you will be able to use state management to increment the counter using Redux. Redux library has all that it requires for store management and react-redux binds react and redux libraries together.

The store management with redux has 3 main components:

- Actions - These are blocks of information that send data from your application to your store. Actions must have a type property that indicates the type of action being performed.

- Reducers - Reducers specify how the application’s state changes in response to actions sent to the store.

- Store - The Store is the object that brings the action and reducer together. The store has the following responsibilities: holds application state, allows access to state, allows state to be updated via dispatch(action).
