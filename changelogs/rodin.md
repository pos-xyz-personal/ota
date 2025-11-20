# November 20, 2025
- Increase keyguard bottom text
- Refactor automatic brightness values
- Reduce FOD placement
- Switch to xiaomi's vibratorfeature richtap
- Drop soc7 connectivity firmware
- Refactor power HAL, udfpshandler to use xiaomi-touch
- Import gamebar
- Resolve USB tethering

# October 11, 2025
- Update firmware into OS2.0.204.0.VOJMIXM and kernel to 6.6.56
- Partially fixed abd Shipped miuicamera (1080p60/4k60 dies sadly)
- Resolved proximity sensor issue

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
