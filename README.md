# 🚀 Challenge técnico – Bugster  
## ¿MILLONARIA o PIRAMIDAL? 🤔

Este es un challenge técnico corto, divertido y con referencias tech que usamos en Bugster para conocer cómo pensás, diseñás y ejecutás.

---

## 🧠 La idea

Vas a construir una mini app que reciba una idea de startup y, usando un modelo tipo OpenAI, la clasifique como:

> 🚀 **MILLONARIA**  
> 💸 **ESTAFA PIRAMIDAL**

La idea es que te diviertas, hagas algo funcional en poco tiempo, y nos muestres tu criterio de producto.

---

## 🧩 Requisitos del challenge

### ✅ Obligatorios

- Landing page con:
  - Nombre de la app
  - Descripción divertida
  - CTA al login
- Supabase Auth (email, magic link, etc.)
- Textarea para pegar una idea
- Llamada a OpenAI (o modelo similar) que:
  - Clasifique la idea como *millonaria* o *piramidal*
  - Devuelva una explicación corta con humor
- Gating visual:
  - Usuarios **free** pueden testear 1 idea por día
  - Usuarios **pro** pueden testear ilimitado
- Página `/pro` con botón que abre un **modal trucho** de Stripe
  - Al confirmar, actualiza el `user.metadata.plan = 'pro'` en Supabase
- Mensaje en la UI que indique si sos "Free" o "Pro"
- **Deploy funcional en [Vercel](https://vercel.com/)**

---

## 🛠 Stack sugerido

- [Next.js](https://nextjs.org/)
- [Supabase](https://supabase.com/) (auth)
- [OpenAI API](https://platform.openai.com/) o cualquier otro LLM
- UI con lo que quieras: Tailwind, shadcn/ui, etc.

💡 Podés usar herramientas como:
- [v0.dev](https://v0.dev)
- [Cursor](https://www.cursor.sh/)
- [Lovable](https://www.lovable.so/)

¡No penalizamos el uso de plantillas! Usalas si te hacen más ágil.

---

## ⏱ Tiempo estimado

- Está pensado para ~**4 horas de desarrollo efectivo**
- Tenés **hasta 48 horas para enviarlo** desde que lo recibís
- No es necesario que esté perfecto ni terminado — nos importa cómo lo encarás

---

## 📦 Qué tenés que entregar

1. Link al repo público (GitHub o similar)
2. **Deploy funcional en Vercel**
3. README o archivo `NOTAS.md` con:
   - Qué hiciste
   - Qué no llegaste a hacer (pero pensaste)
   - Cómo fue tu enfoque

---

## 🧐 Qué vamos a mirar

- Que la app funcione y tenga buen flujo
- Claridad en la UI
- Enfoque y criterio de producto
  
---

## 🛑 Qué no hace falta

- Tests
- Checkout real de Stripe
- UI perfecta
- Infra sólida

---

💬 Si necesitás más tiempo, escribinos.  
