## **დავალება: “Mini Blog App”**

**აღწერა:**
შექმენი პატარა ბლოგის სტრუქტურა, სადაც იქნება:

1. **მთავარი გვერდი (`/`)** – ბლოგის პოსტების სია.

   * თითო პოსტს ჰქონდეს სათაური და მოკლე აღწერა.
   * თითო პოსტზე დაწკაპებით გადავიდეს პოსტის დეტალებზე.

2. **Dynamic route:**

   * `/posts/[id]/page.tsx`
   * თითო პოსტი გამოვიდეს `id`-ის მიხედვით.

3. **Nested route:**

   * პოსტის გვერდზე ჰქონდეს ქვეგვერდი `/posts/[id]/comments`, სადაც გამოჩნდება კომენტარების სია.

4. **( ) Group routes:**

   * შექმენით `/dashboard/(admin)/users`, `/dashboard/(admin)/posts`, `/dashboard/(public)/stats` მსგავსი სტრუქტურა
    უბრალოდ fake გვერდებით (მაგ. `<h1>Admin Posts Page</h1>`).

5. **Optional Bonus:**

   * დაამატეთ `/about` და `/contact` გვერდები.
   * გამოიყენეთ **layout.tsx** რომ ზოგად სტრუქტურას ჰქონდეს header/footer.


## მინიშნება

```tsx
// Example posts array
const posts = [
  { id: 1, title: "Next.js Routing Explained", desc: "Learn how routing works in Next.js" },
  { id: 2, title: "Dynamic Routes in Action", desc: "Handle URLs dynamically!" },
];
```

```tsx
// Example dynamic route: /posts/[id]/page.tsx
export default function PostPage({ params }: { params: { id: string } }) {
  return <h1>Post ID: {params.id}</h1>;
}
```
