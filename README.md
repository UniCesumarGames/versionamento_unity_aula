<p align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSm1Z7752bOKmBssX_FeVMtjmgG9ghBpxjfvA9DsNsGkQ&s=10" alt="UniCesumar" height="90">
</p>

<h1 align="center">Versionamento Unity — Aula</h1>
<p align="center"><em>Material de aula — Git + Unity (primeiro contato)</em></p>

---

## Para que serve este repositório?

Projeto **didático de versionamento**: um Unity mínimo com um script `Player.cs` para praticar:

- `git clone` / `git status` / `git add` / `git commit` / `git push`  
- Boas práticas com Unity (não versionar `Library/`, `Temp/`, etc.)  
- Colaboração em equipe sem quebrar o projeto

> Este README substitui o texto placeholder (Lorem Ipsum) anterior.

## Tecnologias

| Item | Detalhe |
|------|---------|
| Engine | **Unity 2022.3.1f1** |
| Linguagem | C# |
| Foco | Git + fluxo de aula |

## Estrutura principal

```
Assets/
├── Scripts/Player.cs
└── Scenes/SampleScene.unity
ProjectSettings/
.gitignore
```

## Como abrir (aluno)

1. Unity **2022.3.1f1**  
2. Clone:
   ```bash
   git clone https://github.com/UniCesumarGames/versionamento_unity_aula.git
   ```
3. Abra no Hub → `SampleScene` → **Play** (veja o `Debug.Log("Testando game")`)

## Roteiro rápido de Git (sala)

```bash
git status
# edite Assets/Scripts/Player.cs (ex.: mude a mensagem do Debug.Log)
git add Assets/Scripts/Player.cs
git commit -m "aula: atualiza mensagem do Player"
git push
```

## Regras importantes

- Nunca envie pasta `Library/`  
- Combine com a equipe quem edita a mesma cena  
- Prefira commits pequenos e mensagens claras

---

<p align="center">UniCesumar — Jogos Digitais / Desenvolvimento de Games</p>
