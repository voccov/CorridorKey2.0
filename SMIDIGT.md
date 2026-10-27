# CorridorKey 2.0 × Studio Smidigt

This public fork is the local matte engine used by **Studio Smidigt — Key β**,
a separate background-removal experiment in
[Studio Smidigt](https://github.com/voccov/Studio-Smidigt).

The upstream CorridorKey code and weights are unchanged. Studio Smidigt calls
`infer.py` from an isolated virtual environment and uses the model's **alpha**
only; cutouts are rebuilt from the original photo so vehicle pixels are not
rewritten. The integration, measured results and limitations are documented in
`docs/KEY-VERSION.md` in the Studio Smidigt repository.

- Upstream: https://github.com/nikopueringer/CorridorKey2.0
- One-click setup in the app: `POST /api/key/setup`
- Engine home: `CORRIDORKEY_HOME` or `<Studio Smidigt>/data/engines/CorridorKey`
- License: unchanged from upstream. Free to use, including commercial work;
  not for resale or paid API use; keep the name and license.
