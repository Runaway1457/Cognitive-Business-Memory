# Contributing to Cognitive Business Memory

Obrigado por considerar contribuir! 🎉

## 🚀 Quick Start

1. **Fork** o repositório
2. **Clone** seu fork
3. **Instale** dependências: `bun install`
4. **Crie** uma branch: `git checkout -b feature/minha-feature`
5. **Commit**: `git commit -m 'feat: minha feature'`
6. **Push**: `git push origin feature/minha-feature`
7. **Abra** um Pull Request

## 📋 Código de Conduta

- Seja respeitoso e inclusivo
- Aceite críticas construtivas
- Foque no que é melhor para a comunidade

## 🎨 Style Guide

### Commits

Seguimos [Conventional Commits](https://www.conventionalcommits.org/):

```
feat: nova funcionalidade
fix: correção de bug
docs: documentação
style: formatação
refactor: refatoração
test: testes
chore: manutenção
```

### TypeScript

```typescript
// Use interfaces para objetos
interface Entity {
  id: string;
  name: string;
}

// Use types para uniões
type Status = 'active' | 'inactive';

// Prefira composição
type Node = Entity & { position: Vector3 };
```

### React

```tsx
// Prefira function components
export function MyComponent({ prop }: Props) {
  return <div>{prop}</div>;
}

// Hooks no topo
function Component() {
  const [state, setState] = useState();
  const ref = useRef();
  // ...
}
```

## 🧪 Testes

```bash
# Rodar testes
bun test

# Coverage
bun test:coverage
```

## 📁 Estrutura de Arquivos

```
src/
├── app/           # Next.js App Router
├── components/    # React components
│   ├── ui/        # shadcn/ui (não editar)
│   └── cognitive/ # Componentes do projeto
└── lib/           # Utilitários e lógica
```

## 🔧 Setup de Desenvolvimento

```bash
# Instale Bun (se não tiver)
curl -fsSL https://bun.sh/install | bash

# Clone e instale
git clone https://github.com/seu-usuario/cognitive-business-memory.git
cd cognitive-business-memory
bun install

# Configure ambiente
cp .env.example .env.local
# Adicione ZAI_API_KEY

# Rode
bun run dev
```

## 📝 Pull Request Checklist

- [ ] Código segue o style guide
- [ ] Testes passando
- [ ] Documentação atualizada
- [ ] Commits seguindo Conventional Commits
- [ ] PR description clara

## ❓ Dúvidas

Abra uma [Issue](https://github.com/seu-usuario/cognitive-business-memory/issues)!

---

Obrigado por contribuir! 🙏
