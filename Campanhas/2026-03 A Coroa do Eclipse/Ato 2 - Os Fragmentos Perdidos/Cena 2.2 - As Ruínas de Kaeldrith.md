# 🟡 Cena 2.2 — As Ruínas de Kaeldrith

> **Duração estimada:** 75 min | **Foco:** Dungeon crawl, armadilhas, puzzle, combate
> **Dificuldade:** ★★☆☆ | **Fragmento:** 🟡 Ruínas
> **Trilha:** Ecos de pedra, vento em corredores, música de dungeon

---

## Leitura de Ambientação

> *O caminho ao norte leva por colinas rochosas até um vale escondido. Entre paredes de pedra natural, a entrada de um templo se revela — colunas quebradas flanqueiam uma escadaria descendente, coberta de vinhas secas e pó dos séculos. Símbolos solares desbotados adornam a fachada, mas alguém os desfigurou com tinta negra. A Bússola Solar vibra com força.*
>
> *O silêncio aqui é absoluto. Nem pássaros, nem vento. Apenas o eco dos seus próprios passos.*

---

## Mapa do Dungeon

```
NÍVEL SUPERIOR
══════════════
            ┌───────────┐
            │  ENTRADA   │ ← Escadaria descendente
            │  (Sala 1)  │
            └─────┬──────┘
                  │
            ┌─────┴──────┐
            │ CORREDOR    │ ← Armadilha de dardos
            │ DAS COLUNAS │
            │  (Sala 2)  │
            └──┬──────┬──┘
               │      │
      ┌────────┴┐  ┌──┴────────┐
      │ SALA DOS│  │ SALA DO   │
      │ MURAIS  │  │ BASILISCO │
      │ (Sala 3)│  │ (Sala 4)  │
      └────┬────┘  └───────────┘
           │
     ┌─────┴──────┐
     │ CÂMARA DO  │
     │ FRAGMENTO  │ ← Boss + Puzzle
     │  (Sala 5)  │
     └────────────┘
```

---

## Sala 1: A Entrada

> *A escadaria desce 30 pés em espiral. No final, uma sala octogonal se abre. Quatro estátuas de cavaleiros em armadura solar flanqueiam a passagem adiante. Seus rostos foram arrancados.*

- **Perception DC 14:** Pegadas recentes na poeira — botas de cultistas. Pelo menos 4 pessoas passaram há poucos dias.
- **Investigation DC 12:** Uma das estátuas tem a mão posicionada como se segurasse algo — um item foi removido.
- **Arcana DC 15:** Resíduos de magia de abjuração nas estátuas — as proteções do templo foram desativadas.

Dois cultistas mortos estão no canto (matados por armadilhas mais adiante). Um deles carrega uma nota:

> *"Mestre Valdris, a primeira sala está limpa. As armadilhas adiante são mortais. Perdemos Kael e Dorren. Precisamos de mais homens. — Irmão Voss"*

---

## Sala 2: O Corredor das Colunas

Um corredor de 60 pés com 12 colunas (6 de cada lado). O chão tem ladrilhos com símbolos solares.

### Armadilha: Dardos Envenenados
- **Trigger:** Pisar em ladrilhos SEM símbolo solar
- **Detection:** Perception DC 14 (ladrilhos sem símbolo são 1mm mais altos)
- **Disarm:** Thieves' Tools DC 15 (desativa uma seção de 10 pés)
- **Effect:** +6 to hit, 7 (2d6) piercing + DC 13 CON save ou Poisoned por 1 hora
- **Solução alternativa:** Pisar APENAS nos ladrilhos com símbolo solar (requer Acrobatics DC 12 por seção de 10 pés)

### Encontro Opcional
Se o grupo fizer muito barulho: **2× [[Monstro - Mummy]]** emergem dos sarcófagos nas paredes laterais.

| Criatura | HP | AC | Ataque |
|----------|----|----|--------|
| Mummy 1 | 58 | 11 | Rotting Fist +5 → 10 bludg + 10 necro + mummy rot DC 12 |
| Mummy 2 | 58 | 11 | Dreadful Glare DC 11 WIS → Frightened |

**XP:** 1.400 (350/jogador) — Encontro Médio

---

## Sala 3: A Sala dos Murais

> *As paredes estão cobertas de murais que contam a história dos Cavaleiros Solares. Painéis mostram: a forja da Coroa do Eclipse por um lich, a guerra, a quebra da Coroa em três partes, e o selamento dos fragmentos.*

- **History DC 13:** Os murais revelam que cada fragmento requer um "tributo de luz" para ser liberado — algo que emita luz radiante.
- **Religion DC 15:** O último painel mostra que a Coroa pode ser DESTRUÍDA se todos os três fragmentos forem reunidos em um local sagrado e expostos à luz solar pura durante um eclipse. Isso é uma alternativa ao plano de Miriel.
- **Secret:** Investigation DC 17 → Um painel se move, revelando um compartimento com 1× [[Item - Flame Tongue]] (espada longa) e 1× Poção de Greater Healing.

---

## Sala 4: O Covil do Basilisco

> *Uma caverna natural se abre à direita. O chão está coberto de estátuas incrivelmente realistas — viajantes, animais, até um cultista com expressão de terror congelada no rosto. No fundo da caverna, algo respira pesadamente.*

### Encontro: [[Monstro - Basilisk]]

| Criatura | HP | AC | Ataque |
|----------|----|----|--------|
| Basilisk | 52 | 12 | Bite +5 → 10 piercing + 7 poison |

**XP:** 700 (175/jogador) — Encontro Fácil/Médio

**Mecânica especial — Petrifying Gaze:**
- Início do turno a 30ft com linha de visão → DC 12 CON save
- Falha: Restrained (virando pedra). Próximo turno: DC 12 CON — falha = Petrificado
- **Dica para jogadores espertos:** Espelhos! Investigation DC 12 encontra um escudo polido nas estátuas petrificadas. Se o basilisco ver seu reflexo → mira em si mesmo.

**Tesouro:** Entre as estátuas: 200 po em bolsas, 1× Scroll de *Revivify*, anel ornamental (50 po)

---

## Sala 5: A Câmara do Fragmento

> *A sala circular final é magnífica apesar dos séculos. Um altar de ouro e cristal se ergue no centro, banhado por um feixe de luz que desce de uma abertura no teto. Sobre o altar, flutuando e girando lentamente, está um fragmento de cristal negro que pulsa com energia sombria — o Fragmento das Ruínas.*
>
> *Mas o altar está protegido por um círculo de runas luminosas. E do outro lado da sala, sentados em meditação, estão quatro figuras encapuzadas de negro.*

### Encontro: Cultistas da Ordem da Lua Negra
**1× [[Monstro - Cult Fanatic]] + 3× Cultists (CR 1/8, HP 9, AC 12)**

O Cult Fanatic (Irmão Malakai) tenta negociar: "O fragmento pertence ao Mestre Valdris. Vocês podem ir embora vivos."

Se o combate iniciar:

| Criatura | HP | AC | Ataque |
|----------|----|----|--------|
| Cult Fanatic | 22 | 13 | Dagger +4, *Hold Person* DC 11, *Spiritual Weapon* |
| Cultist ×3 | 9 | 12 | Scimitar +3 → 4 slashing |

**XP:** 625 (156/jogador) — Encontro Fácil
**Tática:** O Fanatic usa *Hold Person* no fighter e *Spiritual Weapon* enquanto Cultists flanqueiam.

### O Puzzle do Altar

Após derrotar os cultistas, as runas bloqueiam o fragmento. Para acessá-lo:

**Puzzle: O Tributo de Luz**
O círculo de runas tem 4 pedestais com símbolos: Sol, Lua, Estrela, Eclipse.
- Ativar os pedestais na ordem **Sol → Estrela → Lua → Eclipse** (a progressão da luz à escuridão)
- Pista nos murais (Sala 3): History DC 13 dava a sequência
- **Solução alternativa:** Usar a Bússola Solar para lançar *Daylight* sobre o altar desativa as runas

Se a ordem errada for ativada: 4d6 dano radiante em todos a 15 pés (DEX DC 14 para metade).

---

## Tesouro Total das Ruínas

- 🟡 **Fragmento das Ruínas** (ver [[01 - Visão Geral]])
- [[Item - Flame Tongue]] (Sala 3 — se encontraram o compartimento secreto)
- 280 po total
- 1× Scroll de Revivify
- 1× Potion of Greater Healing

---

**Próximo fragmento:** [[Cena 2.1 - O Pântano dos Sussurros]] ou [[Cena 2.3 - A Floresta do Véu Negro]]
← [[00 - Índice da Campanha]]

#ato2 #dungeon #armadilhas #basilisk #puzzle #fragmento
