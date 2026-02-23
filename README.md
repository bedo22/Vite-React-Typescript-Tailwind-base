You can use Shadcn Create for one command Setup:
npx shadcn@latest create --preset "https://ui.shadcn.com/init?base=radix&style=nova&baseColor=neutral&theme=neutral&iconLibrary=lucide&font=inter&menuAccent=subtle&menuColor=default&radius=default&template=vite&rtl=false" --template vite

Or

Run the CLI
Run the shadcn init command to setup your project:

pnpm
npm
yarn
bun
npx shadcn@latest init
Copy
You will be asked a few questions to configure components.json.

Copy
Which color would you like to use as base color? › Neutral
Add Components
You can now start adding components to your project.

pnpm
npm
yarn
bun
npx shadcn@latest add button
Copy
The command above will add the Button component to your project. You can then import it like this:

src/App.tsx
Copy
import { Button } from "@/components/ui/button"
 
function App() {
  return (
    <div className="flex min-h-svh flex-col items-center justify-center">
      <Button>Click me</Button>
    </div>
  )
}
 
export default App
