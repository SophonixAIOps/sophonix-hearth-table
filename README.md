# Hearth & Table app

Deploy:
  npm i -g vercel
  vercel login
  vercel --prod

AI restaurant assistant (Groq):
  Vercel > Project > Settings > Environment Variables
  GROQ_API_KEY = <your key>   (mark Sensitive, all environments), then redeploy.
  Optional: GROQ_MODEL (default llama-3.3-70b-versatile).
  Without the key the assistant still works on its built-in menu logic.

Personalized link for a lead (name from the path, city and theme optional):
  https://sophonix-hearth-table.vercel.app/lone-star-smokehouse?c=Dallas,%20TX&t=bordeaux
  Themes: olive, bordeaux, espresso, coastal, forest. Or any hex: &color=7A2E1F

Light theme by default; the moon button switches to dark.
Staff sign-in: footer link, PIN 2468 (or press Shift+O).
