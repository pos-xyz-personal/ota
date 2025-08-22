# August 22, 2025
- Import missing EEA's audio_params
- Add UclampTAMin to FIXED_PERFORMANCE action
- Yet another SF tuning
- Optimize HWUI properties
- Boost big cluster on EXPENSIVE_RENDERING

# July 27, 2025
- Ship MtkInCallService
- Switch back to proprietary MTK IMS
- Add GPUBlockBoost node on powerhint
- Disable GED KPI
- Remove CDMA support (resolves IMEI/RIL global variant issue)
- Minor changes on source and stability improvement

# July 22, 2025
- Tweak surfaceflinger properties
- Resolve screen-off udfps
- Use FUSE passthrough by default
- Enable zygote critical window
- Setup display color compositions
- Add AOSP color properties
- Switch to lineage libperfmgr
- Switch to xiaomi-touch node for DT2W
- Switch to udfps_optical for fingerprint type
- Reduce system server verbosity
- Supress citsensor logspams
- Downscale task snapshots to 70%
- Optimize media configs

# July 16, 2025
- Resolve GNSS delay issue
- Sync with stock SF properties
- Upref blobs, kernel to OS2.0.202.0.VOGEUXM
- Enable aux cameras on Aperture
- Import misound stack

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
