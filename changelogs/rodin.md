# October 04, 2025
- Resolved HDR
- Resolved in-call volume
- Fixup missing symlinks
- Fixup dolby audios
- Fixup SoFOD on focaltech displays
- Added and resolved thermal profiles (XMParts)
- Dropped MiuiCamera
- Minor optimizations and stability improvement

# September 18, 2025
- Shipped MiuiCamera
- Shipped JamesDSP
- Enable aux cameras on Aperture (unlocks ultrawide and 2160p60)
- Resolve brightness overlays

NB: MiuiCamera cannot take a picture, but video is working fine. Also the bokeh mode doesn't work neither, Use Aperture instead to take some picture.

# September 12, 2025
- Shipped Dolby Atmos
- Resolve small audio strength (dirty workarounds)
- Resolved fast charging
- Resolved hotspot overlays
- Moved to Lineage lights common HAL
- Disable game default frame rate feature
- Enable ZRAM

# September 8, 2025
- Tune-out the powerhint
- Enable HWUI optimizations
- Downscale task snapshots into 70%
- Offload WM shell to another thread
- Disable alpha compositing in WM
- Move HWC into foreground tasks
- Use foreground Uclamp cpusets for HWC
- Import more GPU stacks
