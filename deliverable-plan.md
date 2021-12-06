1. **hookup supabase**

- [x] add blogs.js in services directory
- [x] export `getBlogs` function which calls supabase
  - _very_ similar to `getRestaurants` in demo

2. **hookup supabase call to your component**

- [x] create `blogs` state using `useState`
- [x] use `useEffect` to call `getBlogs` when the page initially renders
- [x] set the response from `getBlogs` as your `blogs` state
- [x] console.log to make sure this is all working

3. **do the stuff from last week**

- loop through the `blogs` state variable and render a `<BlogCard>` component for each item in blogs
