<!-- LOVABLE:BEGIN -->
> [!IMPORTANT]
> This project is connected to [Lovable](https://lovable.dev). Avoid rewriting
> published git history — force pushing, or rebasing/amending/squashing commits
> that are already pushed — as it rewrites history on Lovable's side and the
> user will likely lose their project history.
>
> Commits you push to the connected branch sync back to Lovable and show up in
> the editor, so keep the branch in a working state.
<!-- LOVABLE:END -->

# Rules

- Reminders are stored in the browser via localStorage (`birthday-anniversary-reminders-v1`), with all date logic client-side in `src/lib/reminders.ts`; there is no backend by design.
- All UI styling uses the "Playful pop cards" semantic tokens in `src/styles.css` (cream/ink/magenta/lemon/aqua/grape/mint, `shadow-pop*`, Fredoka display + Nunito body) — never hardcode colors or shadows in components.
- The reminder app contains only the user-specified features plus the approved small delete control; do not add extras.
