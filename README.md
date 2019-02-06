![](img/logo.svg)

# StringTheory

Identifies opportunities to improve heap memory consumption by strings.

Finds duplicate strings and provides ways to see what object graphs are keeping them alive.

Once you identify a suspicious referrer, you can query to see what other strings it is holding across the whole heap, and the total number of wasted bytes.

## TODO

- [ ] 👩‍💼 Documentation and screenshots
- [ ] 👩‍💼 Show progress during scans
- [ ] 🚀 Parallel heap scans
- [ ] 🚧 Push ClrMD changes upstream
- [ ] 💡 Investigate distribution methods (e.g. ClickOnce)
