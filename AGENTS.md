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
# Project
- Review analysis runs in a server function calling the AI gateway; aggregation/insights are pure functions in src/lib/absa-aggregate.ts (tested) so counts never depend on the model.
- Evaluation metrics live in src/lib/metrics.ts and must only hold measured values supplied by the user.
