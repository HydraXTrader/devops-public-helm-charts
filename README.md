# devops-public-helm-charts

HydraX public Helm charts.

Repository URL: https://hydraxtrader.github.io/devops-public-helm-charts

Available charts:
- [metabase](charts/metabase)

## Publish a New Version
1. Mofify chart template files inside [charts/](charts/) directory.
2. Don't forget to bump up chart version inside `Chart.yaml`.
3. Create a new PR.
4. After PR has been merged, GitHub Actions will pick up changes inside `charts/` directory and publish a new version.