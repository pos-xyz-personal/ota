# July 12, 2025
- Resolve jiiov fingerprint sensor (finally)
- Configure citsensor stack (sybau, logspam)
- Import missing radio stack

# July 11, 2025
- Switch back to GpuPwrLevel for GPU boosting
- Tweak LMKD settings
- Drop debug.sf.enable_transaction_tracint
- Stop forcing triple framebuffers
- Prefer HW media codecs over SW.
- Import RSC properties
- Import missing GNSS init (not sure if GPS is fixed)

# 4 July 2025
- Import libmisoundcrossfade stack
- Set nr_requests to 64 for Storage
- Tune-out the power hint for performance and efficiency, pretty much changes
- Set config_sustainedPerformanceModeSupported
- Configure powerhal properties
- Address gpu nodes

# June 30, 2025
- Drop DSPVolumeSynchronizer
- Rework audio & USB Audio configuration
- Move to MTK memtrack
- Don't startup Dolby service at boot
