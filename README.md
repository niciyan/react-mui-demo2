### Reference

- https://www.youtube.com/watch?v=fzxEECHnsvU

### Development

- VSCode
- Dev Container(Node & Typescript)

### Note

Because `src/components/Sidebar.tsx` was originally written by js (not Typescript),
I had an type error.
So, I had to rewrite code using props.

```
interface SidebarProps {
  mode: string;
  setMode: React.Dispatch<SetStateAction<string>>;
}

const Sidebar = (props: SidebarProps) => {
```
