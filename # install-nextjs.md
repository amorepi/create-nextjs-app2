# How to deploy Next.js App on Vercel

### Progetto: create-nextjs-app

#### Reference: [nextjs.org](https://nextjs.org) e [How to deploy Next.js App on Vercel](https://www.youtube.com/watch?v=YVqdpSsCnK4)

### Dominio: ingamore.cloud

### Start Learning: [Start building with Next.js](https://nextjs.org/learn?utm_source=next-site&utm_medium=homepage-cta&utm_campaign=home)

### Node: v22.15.0

## Fase 1: Creazione del progetto

### Aprire Terminal e collocarsi in ˜/desktop/develop

### Eseguire: npx create-next-app@latest

### Accettare nelle seguenti richieste i valori di default:

```
✔ What is your project named? … [create-nextjs-app]
✔ Would you like to use TypeScript? … No / [Yes]
✔ Would you like to use ESLint? … No / [Yes]
✔ Would you like to use Tailwind CSS? … No / [Yes]
✔ Would you like your code inside a `src/` directory? … [No] / Yes
✔ Would you like to use App Router? (recommended) … No / [Yes]
✔ Would you like to use Turbopack for `next dev`? … [No] / Yes
✔ Would you like to customize the import alias (`@ / *` by default)? … [No] / Yes
Creating a new Next.js app in /Users/piero/Desktop/Develop/create-nextjs-app.
Using npm. Initializing project with template: app-tw

```

### Il risultato ottenuto è

```
Installing dependencies:
- react
- react-dom
- next

Installing devDependencies:
- typescript
- @types/node
- @types/react
- @types/react-dom
- @tailwindcss/postcss
- tailwindcss
- eslint
- eslint-config-next
- @eslint/eslintrc
```

### Eseguire: cd create-nextjs-app

### Nel file .gitignore, inserire dopo node_modules, la riga: install*.md

### Eseguire: npm run dev

### Eseguire [http://localhost:3000](http://localhost:3000)

## Fase 2: Creazione del progetto su GitHub

### Effettuare accesso autorizzato su GitHub.com

### Clic sul pulsante New

### Assegnare Repositary name: create-nextjs-app, type: Private

### Clic su Create repository

### Nella nuova pagina copiare i comandi dell'ultima soluzione:

git remote add origin https://github.com/amorepi/create-nextjs-app.git
git branch -M main
git push -u origin main

### Sul Terminal verificare di essere collocato nella directory del progetto

### Incollare ed eseguire i comandi copiati

## Fase 2: Da GitHub clonare in locale il presente progetto

1. ### Aprire Terminal e collocarsi in ˜/Progetti
2. ### Esegui: git clone https://github.com/amorepi/create-react-app.git
3. ### Inserire il nome di questo file (install.md) nel file .gitignore
4. ### Esegui: git add .
5. ### Esegui: git commit -m 'first commit’
6. ### Esegui: git branch -M main
7. ### Esegui: git remote add origin https://github.com/amorepi/express-node-vercel.git
8. ### Esegui: git push -u origin main
9. ### Esegui: Clic su Create repository

## Fase 3: Collegamento del progetto per un deploy su Vercel

1. ### Su Vercel.com accedere all'elenco dei progetti ([https://vercel.com/pietro-amores-projects](https://vercel.com/pietro-amores-projects))
2. ### Clic sul nome del progetto "create-react-app"
3. ### Nella finestra successiva, clic nel pulsante del menu "Domains"
4. ### Clic sul pulsante "Add Domain"
5. ### Nel combobox selezionare il dominio "ingamore.com"
6. ### Disattivare il checkbox sottostante di Redirect
7. ### Clic sul pulsante "Add Domain" e poi un clic su "Save"
8. ### Accedere a Hostinger.com e alla gestione del dominio citato
9. ### nel pannello centrale, clic su Modificare della voce DNS/Nameserver
10. nel tipo (CNAME) / nome (www) modifica contenuto con cname.vercel-dns.com
11. ### nel tipo (A) → 76.76.21.21

# Note:

---
