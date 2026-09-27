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

- Keep event facts and the registration target in `src/lib/event-config.ts`; this avoids conflicting event details across the single-page experience.
- Build character visuals with CSS/SVG and replaceable artwork slots, not generated or copyrighted imagery; this keeps the concept portable and easy to art-direct later.
