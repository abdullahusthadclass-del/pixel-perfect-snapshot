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

- Astronomy math lives in src/lib/astronomy (pure, unit-tested); 3D components only render its output — keeps geometry verifiable.
- Observer-local frame is fixed: +X East, +Y Zenith, -Z North — all layers and labels depend on it.
