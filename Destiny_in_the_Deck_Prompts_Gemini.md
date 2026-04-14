# 🎮 DESTINY IN THE DECK — Prompts para Gemini (Pixel Art 16-bit)
**Documento de Produção Visual · Fork Games St.**
**Engenharia de Prompt v1.0**

---

## ⚙️ COMO USAR ESTE DOCUMENTO

Este documento está dividido em dois tipos de entrega visual:

| Tipo | Ícone | O que é | Como usar no Gemini |
|---|---|---|---|
| **Background Estático** | 🖼️ | Uma única imagem de fundo para a cena | Cole o prompt diretamente no Gemini e gere **1 imagem** |
| **Cutscene** | 🎬 | Sequência de quadros que narram um momento | Gere cada **frame separadamente**, em ordem, um prompt por vez |

### Regra de ouro para Cutscenes no Gemini:
> Cole o **PROMPT BASE DA CUTSCENE** primeiro e gere o Frame 1. Depois, em um **novo turno no mesmo chat**, cole o mesmo Prompt Base substituindo apenas a descrição do frame. Isso mantém consistência visual entre os quadros.

---

## 🎨 PROMPT BASE GLOBAL — Cole antes de QUALQUER geração

> **⚠️ INSTRUÇÕES:** Este bloco deve ser inserido no início de TODA geração de imagem neste projeto. Ele garante consistência visual em todo o jogo.

```
Style guide — always apply to every image in this project:
Pixel art, 16-bit SNES/Super Famicom aesthetic. Warm and melancholic color palette 
inspired by Japanese slice-of-life. Tile-based environments. Characters with 
approximately 32x32 to 48x48 pixel sprite resolution. Clean outlines, limited but 
expressive color palette per scene (max 32 colors). Soft dithering for shadows and 
gradients. No anti-aliasing. Cinematic framing. Aspect ratio 16:9. Resolution hint: 
320x180 upscaled. Setting: Japan, year 2000 onwards. Mood: nostalgic, contemplative, 
bittersweet. UI elements must NOT appear in the image. No text, no HUD, no dialogue 
boxes — pure scene art only.
```

---

---

# 🌸 PRÓLOGO

## 🖼️ BACKGROUND ESTÁTICO — Cidade Natal (Tela de Abertura)

**Quando usar:** Tela de título / abertura do jogo, antes de qualquer escolha.

**Como usar no Gemini:** Gere **1 imagem única**.

```
[APPLY GLOBAL STYLE GUIDE]

Scene: A quiet, picturesque Japanese suburban town in the year 2000. Wide establishing 
shot from a slightly elevated angle. Cherry blossom trees lining a residential street. 
Traditional houses mixed with modest 2000s Japanese architecture. A bicycle leaning 
against a fence. Warm golden afternoon light. Children's park visible in the background. 
Power lines crossing the sky. The atmosphere is peaceful, ordinary, and full of 
unspoken potential. No characters visible — this is an empty world waiting for a story.
Pixel art 16-bit, SNES aesthetic, warm nostalgic palette of soft oranges, pinks and blues.
```

---

## 🖼️ BACKGROUND ESTÁTICO — Quarto do Protagonista (12 anos)

**Quando usar:** Fundo da tela de introdução dos amigos no Prólogo.

```
[APPLY GLOBAL STYLE GUIDE]

Scene: A Japanese boy's bedroom in year 2000, belonging to a 12-year-old from a 
middle-class family. A small desk with school books, a game console visible on a shelf, 
posters on the wall, a window showing the neighborhood outside with afternoon light 
filtering in. Futon rolled to the side. School bag on the floor. The room feels lived-in, 
warm and nostalgic. No character present. Interior shot, slightly wide angle to show 
the full room environment.
```

---

---

# 📚 EVENTO 1 — A Primeira Grande Decisão (12 anos)

## 🖼️ BACKGROUND ESTÁTICO — Sala de Aula / Corredor Escolar

**Quando usar:** Fundo durante a narração e apresentação das escolhas do Evento 1.

```
[APPLY GLOBAL STYLE GUIDE]

Scene: Interior of a Japanese middle school hallway, year 2000. Rows of lockers, 
a bulletin board with exam schedules and motivational posters in Japanese. Natural 
light coming through large windows at the end of the corridor. Clean linoleum floors. 
The hallway is empty — early morning before classes. Atmosphere: quiet anticipation, 
the weight of decisions not yet made. Color palette: cool blues and institutional 
greens, warm light from the windows creating contrast.
```

---

## 🎬 CUTSCENE — Escolha A (Estudar Intensamente)

**Quando usar:** Animação de confirmação após o jogador escolher a Opção A.
**Frames:** 3 imagens. Gere uma de cada vez no mesmo chat do Gemini.

---

**🎬 Frame 1/3 — O início do sacrifício**
```
[APPLY GLOBAL STYLE GUIDE]

Cutscene frame 1 of 3. 
Scene: A 12-year-old Japanese boy sitting alone at his desk late at night. Stack of 
thick study books around him. A small desk lamp as the only light source. Through 
the window, his friends can be seen playing outside in the summer evening. He is 
looking at the books with determined but slightly sad eyes. The contrast between 
the warm outdoor fun and the cold indoor study is the emotional core. Medium shot, 
slightly above eye level.
```

**🎬 Frame 2/3 — O peso da disciplina**
```
[APPLY GLOBAL STYLE GUIDE]

Cutscene frame 2 of 3. Same 12-year-old Japanese boy, same bedroom as frame 1.
He is now surrounded by crumpled papers and used pencils, head resting briefly on 
his arm, eyes tired but still open. A calendar on the wall has days crossed off. 
The lamp light is warm but isolating. Clock on the wall shows midnight. 
Close-up medium shot on the boy and the desk.
```

**🎬 Frame 3/3 — A recompensa**
```
[APPLY GLOBAL STYLE GUIDE]

Cutscene frame 3 of 3. 
Scene: A school announcement board showing exam results. The same boy, now slightly 
older-looking from stress, stands before it. His name is at the top of the list 
(shown as pixel art Japanese characters, stylized). His expression is a mix of 
exhausted relief and quiet pride. Other students around him react with varying 
emotions. Bright school interior lighting. Wide medium shot.
```

---

## 🎬 CUTSCENE — Escolha B (Aproveitar a Juventude)

**Frames:** 2 imagens.

**🎬 Frame 1/2 — A tarde perfeita**
```
[APPLY GLOBAL STYLE GUIDE]

Cutscene frame 1 of 2.
Scene: Four 12-year-old Japanese boys playing together in an open park on a warm 
summer afternoon. Lush green trees, a river visible in the background, cicadas 
implied by the heat shimmer in the air. The boys are laughing — one on a bicycle, 
one throwing something, two others watching. Golden hour light. The scene radiates 
pure, uncomplicated joy. Wide shot to capture the full environment and all characters.
```

**🎬 Frame 2/2 — O eco do passado**
```
[APPLY GLOBAL STYLE GUIDE]

Cutscene frame 2 of 2.
Scene: Same park location as frame 1, but now slightly emptier and the protagonist 
is alone, sitting on a bench. He is older (appears 15-16). He looks at the empty 
space where his friends used to play, a faint nostalgic smile on his face. Afternoon 
light fading into dusk. The mood is bittersweet — happy memories tinged with the 
passage of time. Medium shot.
```

---

## 🎬 CUTSCENE — Escolha C (Dedicar-se ao Esporte)

**Frames:** 2 imagens.

**🎬 Frame 1/2 — O treino solitário**
```
[APPLY GLOBAL STYLE GUIDE]

Cutscene frame 1 of 2.
Scene: A 12-year-old Japanese boy training alone in an outdoor sports field at dawn. 
He could be running, kicking a ball, or practicing a martial art — leave the specific 
sport ambiguous (generic athletic motion). Long morning shadows. The field is mostly 
empty except for him. Expression: focused, purposeful, at peace with the solitude. 
His school bag is tossed to the side of the field. Wide establishing shot.
```

**🎬 Frame 2/2 — O corpo que responde**
```
[APPLY GLOBAL STYLE GUIDE]

Cutscene frame 2 of 2.
Scene: The same boy, now visibly more athletic and confident, standing tall on the 
same sports field. His posture has changed — broader shoulders, steady stance. 
Warm afternoon light, long shadows. Other students practice in the background. 
He looks directly forward, calm and grounded. Medium shot, slightly low angle to 
emphasize his quiet strength.
```

---

---

# 🌸 EVENTO 2 — O Encontro no Caminho da Escola (15 anos)

## 🖼️ BACKGROUND ESTÁTICO — Rua da Escola (Manhã de Primavera)

**Quando usar:** Fundo principal durante a narração do Evento 2. Esta é uma das cenas mais importantes do jogo — ela define a FLAG YUI.

```
[APPLY GLOBAL STYLE GUIDE]

Scene: A quiet Japanese residential street in early spring morning. Cherry blossom 
trees in full bloom line both sides of the street. Soft pink petals falling. Warm 
morning light with slight mist. Traditional houses and small shops on either side. 
A school route — students bags and bicycles implied by details in the environment. 
The scene is beautiful but carries a subtle unease — something is about to happen 
here. Wide establishing shot. No characters.
```

---

## 🎬 CUTSCENE — O Momento de Yui (Comum a todas as escolhas do Evento 2)

**Quando usar:** Antes de apresentar as opções. Esta cutscene é a mesma independente da escolha — ela apresenta a situação.
**Frames:** 3 imagens.

**🎬 Frame 1/3 — A cena da intimidação**
```
[APPLY GLOBAL STYLE GUIDE]

Cutscene frame 1 of 3. Emotional core scene — handle with care and dignity.
Scene: On a cherry-blossom lined school street in spring morning, a 15-year-old 
Japanese girl (Yui) stands surrounded by three older teenage boys. The boys' body 
language is threatening — invading her space, leaning in. Yui stands composed but 
her eyes show fear. Passersby on the street are looking away or walking past. 
The contrast between the beautiful spring setting and the threatening situation 
is the visual tension. Wide shot to show the full street context. No graphic violence.
```

**🎬 Frame 2/3 — O protagonista vê a cena**
```
[APPLY GLOBAL STYLE GUIDE]

Cutscene frame 2 of 3.
Scene: A 15-year-old Japanese boy (the protagonist) has stopped walking on the 
same cherry blossom street. His school bag on his shoulder. He is looking toward 
the confrontation (implied off-frame left). His expression is caught between 
hesitation and conscience — frozen in the moment of decision. Close-up on his 
face and upper body. Falling cherry blossom petals around him. Shallow depth of 
field effect via pixel art blur/dithering in background.
```

**🎬 Frame 3/3 — O olhar de Yui**
```
[APPLY GLOBAL STYLE GUIDE]

Cutscene frame 3 of 3.
Scene: Close-up on Yui's face (the 15-year-old girl). She is looking directly at 
the viewer/protagonist. Her expression is complex — fear, dignity, a silent plea. 
Cherry blossoms framing the shot. This image should feel like a memory burned into 
the protagonist's mind. Soft focus background with the street scene. This is the 
image the protagonist will remember for 15 years.
```

---

## 🎬 CUTSCENE — Resultado Escolha A (Ignorar)

**Frames:** 1 imagem.

**🎬 Frame 1/1 — A culpa que fica**
```
[APPLY GLOBAL STYLE GUIDE]

Cutscene frame 1 of 1.
Scene: The protagonist's back as he walks away down the cherry blossom street. 
He is walking in the foreground, moving away from us. In the background, blurred 
and small, the situation with Yui continues. He does not look back. Falling petals. 
The composition deliberately places the protagonist small against the beautiful, 
indifferent world. Wide shot, slightly overhead angle to emphasize isolation and 
moral weight. The mood is heavy despite the beauty around him.
```

---

## 🎬 CUTSCENE — Resultado Escolha B (Chamar a Polícia)

**Frames:** 2 imagens.

**🎬 Frame 1/2 — O gesto responsável**
```
[APPLY GLOBAL STYLE GUIDE]

Cutscene frame 1 of 2.
Scene: The protagonist approaching a police car parked at a street corner. He is 
speaking urgently to an officer through the car window. Morning light. Cherry 
blossoms in the background. His expression is serious and concerned. Medium shot 
from the side. The police car has simple pixel art Japanese police livery.
```

**🎬 Frame 2/2 — Yui liberada, à distância**
```
[APPLY GLOBAL STYLE GUIDE]

Cutscene frame 2 of 2.
Scene: From a distance, across the cherry blossom street, the police are intervening 
with the group of boys. Yui stands free, slightly apart from the situation. The 
protagonist watches from further away — he helped, but anonymously. He is a small 
figure in the foreground watching the resolution unfold in the middle distance. 
Warm spring light. A sense of quiet satisfaction but also distance.
```

---

## 🎬 CUTSCENE — Resultado Escolha C (Intervir Diretamente)

**Frames:** 2 imagens. **Esta é a mais importante do jogo.**

**🎬 Frame 1/2 — A intervenção**
```
[APPLY GLOBAL STYLE GUIDE]

Cutscene frame 1 of 2. This is a pivotal scene — composed with cinematic weight.
Scene: The protagonist (15 years old) stands between Yui and the group of older 
boys on the cherry blossom street. His posture is open, calm, non-aggressive but 
firm. He is speaking to the boys (mouth slightly open). The boys are in the 
background, slightly smaller — the composition places the protagonist between 
them and Yui in a protective triangle. Falling petals. Morning golden light. 
No physical violence — this is resolved by presence and voice alone.
```

**🎬 Frame 2/2 — O olhar que não precisa de palavras**
```
[APPLY GLOBAL STYLE GUIDE]

Cutscene frame 2 of 2. The most emotionally significant image in the early game.
Scene: The protagonist and Yui standing on the now-empty cherry blossom street. 
The boys are gone. They are standing a respectful distance apart, facing each 
other. Yui is looking at him — not smiling, not speaking, but her eyes carry 
everything. He holds her gaze quietly. Cherry blossoms fall between them. 
Warm spring light. This image should feel timeless — like a photograph someone 
keeps for 15 years. Medium shot, slightly wider to include the full spring street.
```

---

---

# 🎓 EVENTO 3 — O Fim do Ensino Médio (18 anos)

## 🖼️ BACKGROUND ESTÁTICO — Cerimônia de Formatura

**Quando usar:** Fundo durante a narração do Evento 3.

```
[APPLY GLOBAL STYLE GUIDE]

Scene: Interior of a Japanese high school gymnasium set up for a graduation ceremony. 
Rows of chairs with students in black uniforms (gakuran for boys). A stage with a 
podium at the front. Banners and decorations. Soft natural light from high windows 
mixed with indoor lighting. The room is full but the focus is on the environment — 
the chairs, the stage, the light — not on individual faces. The mood is ceremonial, 
nostalgic, the end of something and the beginning of something unknown. Wide shot.
```

---

## 🎬 CUTSCENE — A Noite de Despedida dos Quatro Amigos

**Quando usar:** Transição antes das escolhas do Evento 3.
**Frames:** 2 imagens.

**🎬 Frame 1/2 — Os quatro juntos pela última vez**
```
[APPLY GLOBAL STYLE GUIDE]

Cutscene frame 1 of 2.
Scene: Four 18-year-old Japanese young men sitting together at a small izakaya 
table at night. Warm lantern light. Beer glasses and food on the table (non-alcoholic 
drinks acceptable given age, but the izakaya atmosphere is key). They are laughing — 
the easy, comfortable laughter of people who have known each other for years. The 
background shows other customers, a wooden interior, traditional lanterns. This is 
the last time they are all truly in the same place with the same future ahead. 
Wide table shot.
```

**🎬 Frame 2/2 — A pergunta que pesa**
```
[APPLY GLOBAL STYLE GUIDE]

Cutscene frame 2 of 2.
Scene: The same izakaya table, but now the mood has shifted. The four young men 
are looking at the protagonist — their expressions range from curious to expectant. 
Ryuji looks confident and slightly challenging. Kenji looks serious and supportive. 
Kouta looks calm and already at peace with his own path. The protagonist is in 
the foreground, back to us or partially visible, facing his three friends. 
The question "And you?" hangs in the air. Medium shot across the table.
```

---

---

# 💼 EVENTO 4 — A Crise dos Vinte e Poucos (24 anos)

## 🖼️ BACKGROUND ESTÁTICO — Apartamento Pequeno (Noite)

**Quando usar:** Fundo principal do Evento 4. É o cenário mais urbano e solitário do jogo até aqui.

```
[APPLY GLOBAL STYLE GUIDE]

Scene: Interior of a small Japanese studio apartment at night. A single young man's 
living space — minimal furniture, a kotatsu table, takeout containers, a laptop 
open with spreadsheets or work documents glowing. City lights visible through the 
window — a medium-sized Japanese city at night, neon signs, apartment buildings. 
The apartment is clean but impersonal, the space of someone who works too much to 
truly live in it. The emotional tone: exhausted, uncertain, quietly struggling. 
The city outside glows indifferently. No character present. Wide interior shot.
```

---

## 🎬 CUTSCENE — A Janela de Sexta-Feira

**Quando usar:** Transição narrativa antes das escolhas do Evento 4.
**Frames:** 1 imagem.

**🎬 Frame 1/1 — O homem e a janela**
```
[APPLY GLOBAL STYLE GUIDE]

Cutscene frame 1 of 1.
Scene: A 24-year-old Japanese man standing at the window of his small apartment 
at night, looking out at the city. He is seen from behind or in silhouette profile. 
Suit jacket tossed on the couch behind him, loosened tie. The city outside is alive 
with lights — he is still, contemplative. The contrast between the vibrant city 
outside and his stillness inside is the visual tension. This is the moment before 
a decision. Cinematic wide shot, slightly behind him.
```

---

---

# 💍 EVENTO 5 — A Decisão Social (30 anos)

## 🖼️ BACKGROUND ESTÁTICO — Restaurante Japonês (Noite)

**Quando usar:** Fundo da narração principal do Evento 5.

```
[APPLY GLOBAL STYLE GUIDE]

Scene: Interior of a refined but not overly fancy Japanese restaurant at night. 
Soft warm lighting from paper lanterns. Wooden decor, low tables, a few other 
couples and small groups dining. The atmosphere is intimate and quiet. 
A single empty seat visible in the foreground — the protagonist's perspective. 
Across the restaurant, visible but not yet in focus, a woman is seated alone. 
The restaurant feels like the kind of place where important things happen quietly. 
Wide shot establishing the environment.
```

---

## 🎬 CUTSCENE — O Reencontro com Yui

**Quando usar:** Momento ANTES do bloco condicional — todos os jogadores veem isso.
**Frames:** 2 imagens.

**🎬 Frame 1/2 — O reconhecimento**
```
[APPLY GLOBAL STYLE GUIDE]

Cutscene frame 1 of 2. This scene carries 15 years of narrative weight.
Scene: In a Japanese restaurant at night, a 30-year-old Japanese man has frozen 
mid-movement — his eyes have found something across the room. His expression is 
one of sudden recognition, as if time has collapsed. In the background, partially 
visible through restaurant patrons, a 30-year-old Japanese woman (Yui) — elegant, 
poised, clearly successful — is also looking up. Their eyes have found each other 
across the room. The moment is suspended. Warm restaurant lighting. Medium-wide shot.
```

**🎬 Frame 2/2 — O instante suspenso**
```
[APPLY GLOBAL STYLE GUIDE]

Cutscene frame 2 of 2.
Scene: Close-up split composition — left side shows the protagonist's face (30 years 
old, slightly tired but alive with recognition), right side shows Yui's face 
(composed, intelligent, searching her memory). Between them: the warm blur of the 
restaurant. Both expressions carry the weight of a shared history neither has spoken 
about in 15 years. This is the emotional climax of the first half of the game. 
No dialogue boxes — the image tells everything.
```

---

## 🎬 CUTSCENE CONDICIONAL A — Yui Ajudada Diretamente (yui_ajudada_diretamente = true)

**⚠️ IMPORTANTE:** Este set de frames só é gerado/exibido se a FLAG `yui_ajudada_diretamente` estiver ativa. Use a condicional do sistema de flags para controlar a exibição.

**Frames:** 1 imagem.

**🎬 Frame 1/1 — O sorriso que guarda uma história**
```
[APPLY GLOBAL STYLE GUIDE]

Conditional cutscene — flag: yui_ajudada_diretamente.
Scene: Yui (30 years old) is smiling at the protagonist across the restaurant table. 
Not a polite social smile — a real one, the kind that surfaces a specific memory. 
Her eyes are warm, searching his face for the same person she remembered. 
The restaurant around them has faded — the focus is entirely on her expression 
and the unspoken shared history between them. She is leaning slightly forward, 
engaged, present. Medium shot on Yui's face and upper body.
```

---

## 🎬 CUTSCENE CONDICIONAL B — Yui Ajudada Indiretamente (yui_ajudada_indiretamente = true)

**⚠️ IMPORTANTE:** Exibir apenas se `yui_ajudada_indiretamente` estiver ativa.

**Frames:** 1 imagem.

**🎬 Frame 1/1 — A memória incompleta**
```
[APPLY GLOBAL STYLE GUIDE]

Conditional cutscene — flag: yui_ajudada_indiretamente.
Scene: Yui (30 years old) at the restaurant table, looking at the protagonist with 
slightly furrowed brows — the expression of someone reaching into a memory that 
is almost but not quite there. She is poised and curious, not cold. The protagonist 
is partially visible on the right edge of the frame. The mood is tentative, like 
two people circling a shared story neither knows how to name. Medium shot.
```

---

## 🎬 CUTSCENE CONDICIONAL C — Yui Ignorada (yui_ignorada = true)

**⚠️ IMPORTANTE:** Exibir apenas se `yui_ignorada` estiver ativa.

**Frames:** 1 imagem.

**🎬 Frame 1/1 — A porta fechada**
```
[APPLY GLOBAL STYLE GUIDE]

Conditional cutscene — flag: yui_ignorada.
Scene: Yui (30 years old) has risen from the restaurant table, collected her things. 
She is looking at the protagonist one last time before leaving — her expression is 
polite, impenetrable, and final. Not angry. Just closed. The protagonist remains 
seated, slightly smaller in frame. Other restaurant patrons move around them, 
indifferent. The warm restaurant light feels cold in this moment. Wide shot showing 
both figures and the space between them.
```

---

---

# 🌅 EVENTO 6 — A Grande Proposta (40 anos)

## 🖼️ BACKGROUND ESTÁTICO — A Sala com as Fotos na Parede

**Quando usar:** Fundo principal do Evento 6. Esta é a cena mais introspectiva do jogo.

```
[APPLY GLOBAL STYLE GUIDE]

Scene: Interior of a comfortable, lived-in Japanese family home on a quiet Sunday 
afternoon. A hallway or living room wall covered in framed photographs — school 
years, friends, a wedding photo, a child's first steps in a garden. Soft natural 
light filtering through shoji screens. The home is warm but the wall of photographs 
creates a timeline of a life already half-lived. No character present — the viewer 
inhabits the space. The emotional tone: reflective, slightly melancholic, suspended 
between gratitude and restlessness. Medium interior shot focused on the photo wall.
```

---

## 🎬 CUTSCENE — O Homem Diante das Fotos

**Quando usar:** Momento de transição narrativa antes das escolhas do Evento 6.
**Frames:** 2 imagens.

**🎬 Frame 1/2 — O passado na parede**
```
[APPLY GLOBAL STYLE GUIDE]

Cutscene frame 1 of 2.
Scene: A 40-year-old Japanese man stands in front of a wall of family photographs 
in his home. He is looking at one specific photo — himself as a young man, smiling. 
His current expression is unreadable: not sad, not happy — contemplative in a way 
that goes deeper than both. Sunday afternoon light. He is in casual home clothes. 
From behind or in profile to preserve ambiguity. Medium shot.
```

**🎬 Frame 2/2 — O celular que muda tudo**
```
[APPLY GLOBAL STYLE GUIDE]

Cutscene frame 2 of 2.
Scene: The same man's hand holding a smartphone showing a notification/message 
(content not legible — just glowing screen). In the background, slightly out of 
focus, his wife has appeared in the doorway, watching him quietly. The house is 
peaceful, ordered, safe. The phone glows with something that will disrupt all of 
that. Close-medium shot on the hand with the phone and the doorway beyond. 
Tension between the familiar home and the unknown opportunity.
```

---

---

# 🎹 EVENTO 7 — O Requiem (Final da Jornada)

## 🖼️ BACKGROUND ESTÁTICO — A Festa / O Salão

**Quando usar:** Fundo principal do Evento 7. Esta é a cena mais emocional do jogo.

```
[APPLY GLOBAL STYLE GUIDE]

Scene: A warm, intimate gathering in a traditional Japanese event space or large 
home. Paper lanterns and soft lighting. Round tables with family and friends — 
elderly guests, middle-aged figures, younger generations. At the front of the room, 
a grand piano on a small raised platform. Flowers. The atmosphere is the specific 
warmth of a gathering where everyone has come because they truly wanted to. 
The room is full of life — laughter suggested by body language, conversations 
happening at every table. Wide establishing shot. No central character yet.
```

---

## 🎬 CUTSCENE — O Homem ao Piano

**Quando usar:** Abertura do Evento 7, antes de qualquer escolha.
**Frames:** 3 imagens. **Esta é a sequência mais importante do jogo.**

**🎬 Frame 1/3 — Sentado ao piano**
```
[APPLY GLOBAL STYLE GUIDE]

Cutscene frame 1 of 3. This is the most emotionally significant scene in the game.
Scene: An elderly Japanese man (protagonist, late 70s) sits alone at a grand piano 
in the warm gathering hall. His hands rest on the keys but he has not yet played. 
The party continues around him — people eating, talking — but he is in a private 
world, looking at the keys. Seen slightly from the side and front. The keys stretch 
out before him like a timeline. Soft warm light from above. Medium shot.
```

**🎬 Frame 2/3 — As teclas como memórias**
```
[APPLY GLOBAL STYLE GUIDE]

Cutscene frame 2 of 3.
Scene: Close-up on the elderly protagonist's hands on the piano keys. Aged hands — 
veined, experienced, bearing the marks of a long life. One hand has just pressed 
a key, a single note rippling out. The image is intimate and quiet. The focus is 
entirely on the hands and the keys — everything else is dark or blurred. 
This is 70 years of living distilled into a single note.
```

**🎬 Frame 3/3 — A pergunta do neto**
```
[APPLY GLOBAL STYLE GUIDE]

Cutscene frame 3 of 3.
Scene: A young boy (8-10 years old, the protagonist's grandson) has climbed onto 
the piano bench and sits beside the elderly man. The boy is looking up at his 
grandfather with wide, sincere eyes. The grandfather has stopped playing and is 
looking at the boy. Between them: the piano keys, the warm party light, and 
an unspoken question that fills the whole room. Wide shot to include both figures 
at the piano with the party visible softly in the background.
```

---

## 🎬 CUTSCENE — Os Três Amigos na Primeira Fila

**Quando usar:** Após a pergunta do neto, antes de apresentar as escolhas finais.
**Frames:** 1 imagem.

**🎬 Frame 1/1 — Uma vida inteira em três rostos**
```
[APPLY GLOBAL STYLE GUIDE]

Cutscene frame 1 of 1.
Scene: Three elderly Japanese men sitting in the front row of the gathering — 
Kenji (dignified, composed, the look of a man who served faithfully), Ryuji 
(silver-haired, still carrying ambition even in age, a warm smile now), 
Kouta (calm, solid, content — a man at peace). All three are looking at the 
protagonist (implied off-frame). Their expressions share a single wordless message 
of encouragement and deep affection. The accumulated weight of 60+ years of 
friendship is in their faces. Warm gathering light. Medium wide shot of the three men.
```

---

---

# 🏆 FINAIS — Telas de Encerramento

> **Como usar:** Cada final tem 1 imagem de fundo + 1 cutscene de fechamento. Gere ambas separadamente.

---

## 🌟 FINAL ESPECIAL — O Arquiteto do País

### 🖼️ BACKGROUND ESTÁTICO
```
[APPLY GLOBAL STYLE GUIDE]

Scene: A grand formal setting — a Japanese national hall or official government 
building interior. High ceilings, flags, formal architecture. Morning light 
streaming through tall windows. The space is prepared for a ceremony. 
A podium at the center. The room is vast, impressive, and charged with the weight 
of history being made. No characters — this is the stage before the protagonist 
steps onto it. Wide architectural shot. Palette shifts here toward blues, 
whites and golds — more formal than the warm family tones of the rest of the game.
```

### 🎬 CUTSCENE DE FECHAMENTO (1 frame)
```
[APPLY GLOBAL STYLE GUIDE]

Ending cutscene — Final Especial: O Arquiteto do País.
Scene: The elderly protagonist stands at a podium in a grand Japanese ceremonial 
hall. He is the Prime Minister now — but the image isn't about power, it's about 
completion. Beside him stands Kenji (proud, fulfilled). In the audience, visible: 
Ryuji smiling genuinely for perhaps the first time, Kouta watching with quiet pride. 
The protagonist's wife holds his hand just off-podium. His grandson is in the crowd, 
eyes wide. Morning light through tall windows. The composition should feel earned, 
not triumphant — this is the conclusion of a very long journey. Wide ceremonial shot.
```

---

## ⭐ FINAL 1 — O Equilíbrio Dourado

### 🖼️ BACKGROUND ESTÁTICO
```
[APPLY GLOBAL STYLE GUIDE]

Scene: The gathering hall at the end of the party — later in the evening. 
Lights slightly dimmer, some guests have left, a few small groups remain in 
quiet conversation. The protagonist and his wife are sitting together near the 
window, glasses of tea, soft smiles. The room is winding down — the comfortable 
ending of a good evening. No drama, no revelation — just warmth. 
This is what a life well-lived looks like from the outside: unremarkable and 
completely whole. Medium-wide shot.
```

---

## 💰 FINAL 2 — O Milionário Miserável

### 🖼️ BACKGROUND ESTÁTICO
```
[APPLY GLOBAL STYLE GUIDE]

Scene: The gathering hall — same party as the other endings — but the protagonist 
is standing slightly apart from the crowd. Well-dressed, successful-looking, 
clearly prosperous. But there is a subtle separateness to him — he is in the room 
but not quite of it. Other guests laugh and connect around him. He holds his drink 
and observes. The lighting is warm but the composition is lonely — he occupies 
negative space while life happens in the background clusters behind him. 
The tragedy is invisible unless you know to look. Medium shot.
```

---

## 🌿 FINAL 3 — A Vida Simples e Plena

### 🖼️ BACKGROUND ESTÁTICO
```
[APPLY GLOBAL STYLE GUIDE]

Scene: The gathering is in a smaller, more modest space — perhaps a home garden 
or a simple community hall. Not fancy. But absolutely overflowing with people — 
friends, family, neighbors, generations. The protagonist is surrounded, touched, 
reached for. Laughter everywhere. Simple paper lanterns. Garden greens and warm 
evening light. The modest setting makes the abundance of human connection even 
more striking. This room has no wealth but is full beyond measure. Wide warm shot.
```

---

## ☠️ FINAL 4 — O Burnout Fatal (GAME OVER)

### 🖼️ BACKGROUND ESTÁTICO
```
[APPLY GLOBAL STYLE GUIDE]

Scene: A hospital room. Simple, clean, Japanese public hospital aesthetic. 
A window with natural light — outside, cherry blossoms are barely visible through 
the glass. A bed. Monitoring equipment implied by pixel art objects in background. 
Flowers on the bedside table — placed by family. The room is quiet. 
The outside world continues — the blossoms fall — indifferent to the stillness 
inside. The mood is not grim but sorrowful — a reminder that the body has limits. 
Medium interior shot. Muted palette, cooler tones than the rest of the game.
```

---

## 🌑 FINAL 5 — A Crise Existencial (GAME OVER)

### 🖼️ BACKGROUND ESTÁTICO
```
[APPLY GLOBAL STYLE GUIDE]

Scene: The gathering hall — the party is happening around the protagonist. 
But the composition uses the visual language of absence: he is present in the 
frame but visually isolated. Other guests interact in warm pools of light that 
don't quite reach him. His expression is not sad — it is empty, which is worse. 
His wife watches from across the room, expression worried. His grandson is looking 
at him but doesn't know what he's seeing. The party continues around a still center. 
The composition should feel like a bell jar — surrounded by life, separated from it. 
Wide shot.
```

---

---

# 🎨 SPRITES DE PERSONAGENS

> **Como usar:** Gere estas imagens separadamente para uso como sprites no jogo. Um prompt por personagem, por fase de vida.

---

## Protagonista — Sprite Sheet (4 idades)

**Sprite 1 — 12 anos**
```
[APPLY GLOBAL STYLE GUIDE]

Character sprite sheet — Protagonist, age 12.
A 12-year-old Japanese boy in school uniform (standard Japanese middle school, 
dark jacket, white shirt). Simple, round face with curious eyes. Short black hair. 
Neutral standing pose facing slightly left. Transparent background. 
Pixel art sprite approximately 32x48 pixels, clean outlines, limited color palette. 
Generate 4 poses on the same image: idle, happy, sad, determined.
```

**Sprite 2 — 24 anos**
```
[APPLY GLOBAL STYLE GUIDE]

Character sprite sheet — Protagonist, age 24.
A 24-year-old Japanese man. Office worker appearance — slightly tired eyes, 
dress shirt with collar open, no tie. Leaner face than childhood, slight fatigue. 
Black hair slightly longer. Transparent background. Pixel art sprite 32x48px. 
Generate 4 poses: idle, working (hunched), laughing, exhausted.
```

**Sprite 3 — 40 anos**
```
[APPLY GLOBAL STYLE GUIDE]

Character sprite sheet — Protagonist, age 40.
A 40-year-old Japanese man. Business casual. Hair showing first signs of grey 
at temples. Lines of experience on his face — not old, but marked by time. 
Confident posture. Transparent background. Pixel art sprite 32x48px. 
Generate 4 poses: idle, contemplative, decisive, tender (with one arm out, 
as if holding something precious).
```

**Sprite 4 — Idoso (Final)**
```
[APPLY GLOBAL STYLE GUIDE]

Character sprite sheet — Protagonist, elderly (late 70s).
An elderly Japanese man in formal attire for a special occasion. White hair, 
gentle eyes holding a lifetime of experience. Slight curve to his posture — 
not frail, just shaped by decades. Transparent background. Pixel art sprite 
32x48px. Generate 3 poses: seated at piano, standing with cane, embracing 
someone (arms outstretched).
```

---

## Yui — Sprite (30 anos)

```
[APPLY GLOBAL STYLE GUIDE]

Character sprite sheet — Yui, age 30.
A 30-year-old Japanese woman, successful businesswoman. Elegant but not cold — 
sharp professional attire, composed expression with warmth beneath it. 
Black hair, sharp eyes that carry intelligence and history. Transparent background.
Pixel art sprite 32x48px. Generate 3 poses: neutral/professional, warm smile 
(the one from the restaurant), and turned away (for the yui_ignorada flag outcome).
```

---

## Trio de Amigos — Sprites (18 anos para referência)

```
[APPLY GLOBAL STYLE GUIDE]

Character sprite sheet — Three friends at age 18.
Three distinct 18-year-old Japanese young men, shown side by side on the same image.
LEFT — Kenji: serious face, upright posture, determined eyes. School uniform. 
CENTER — Ryuji: confident smirk, slightly flashy collar, ambitious energy. 
RIGHT — Kouta: calm, solid, gentle expression, practical clothes.
All three have transparent backgrounds. Pixel art sprites 32x48px each. 
Each has 2 poses: idle and their characteristic expression.
```

---

---

# 📋 CHECKLIST DE PRODUÇÃO

Use esta lista para rastrear o progresso das gerações:

## Backgrounds Estáticos
- [x] Cidade Natal (Prólogo)
- [x] Quarto do Protagonista (Prólogo)
- [x] Corredor Escolar (Evento 1)
- [x] Rua Primaveril — Manhã (Evento 2)
- [x] Cerimônia de Formatura (Evento 3)
- [x] Apartamento Pequeno — Noite (Evento 4)
- [x] Restaurante Japonês — Noite (Evento 5)
- [x] Sala com Fotos na Parede (Evento 6)
- [x] Salão da Festa — Requiem (Evento 7)
- [x] Final Especial — Salão Governamental
- [x] Final 1 — Festa ao Fim da Noite
- [x] Final 2 — O Solitário na Multidão
- [x] Final 3 — Festa Simples e Cheia
- [x] Final 4 — Quarto de Hospital
- [x] Final 5 — A Bolha de Vidro

## Cutscenes (total de frames)
- [ ] Evento 1 — Escolha A (3 frames)
- [ ] Evento 1 — Escolha B (2 frames)
- [ ] Evento 1 — Escolha C (2 frames)
- [ ] Evento 2 — Sequência Principal de Yui (3 frames)
- [ ] Evento 2 — Resultado A: Ignorar (1 frame)
- [ ] Evento 2 — Resultado B: Polícia (2 frames)
- [ ] Evento 2 — Resultado C: Intervenção (2 frames) ⭐
- [ ] Evento 3 — Despedida dos Quatro (2 frames)
- [ ] Evento 4 — A Janela de Sexta (1 frame)
- [ ] Evento 5 — Reencontro com Yui (2 frames)
- [ ] Evento 5 — Condicional A: Sorriso (1 frame)
- [ ] Evento 5 — Condicional B: Memória (1 frame)
- [ ] Evento 5 — Condicional C: Despedida (1 frame)
- [ ] Evento 6 — O Homem nas Fotos (2 frames)
- [ ] Evento 7 — O Homem ao Piano (3 frames) ⭐
- [ ] Evento 7 — Os Três Amigos (1 frame)
- [ ] Final Especial — Encerramento (1 frame)

## Sprites
- [ ] Protagonista — 12 anos
- [ ] Protagonista — 24 anos
- [ ] Protagonista — 40 anos
- [ ] Protagonista — Idoso
- [ ] Yui — 30 anos
- [ ] Trio de Amigos — 18 anos

---

*Destiny in the Deck · Fork Games St. · Prompt Engineering v1.0*
*Total: 15 backgrounds · 31 frames de cutscene · 6 sprite sheets*
