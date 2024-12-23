# Next.js 15 Link Component Error

This repository demonstrates a regression in Next.js 15 related to the `next/link` component.  In previous versions, the following usage was valid:

```javascript
<Link href='/about'><a>About Us</a></Link>
```

Next.js 15 now throws an error with this approach.  The solution involves using the `<Link>` component correctly or restructuring the component to not use the `<a>` tag directly.