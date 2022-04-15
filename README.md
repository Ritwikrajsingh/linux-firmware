# lib/firmware
Fix for `W: Possible missing firmware /lib/firmware/amdgpu/`
Fix for `W: Possible missing firmware /lib/firmware/i915/`

## Steps for fixing
### amdgpu
- Open terminal, copy and paste following commads step by step.
- **step 1** `git clone "https://github.com/Ritwikrajsingh/linux-firmware.git"`
- **step 2** `cd linux-firmware-amdgpu/amdgpu`
- **step 3** `cp -a . /lib/firmware/amdgpu/`
- All done.
### i915
- Open terminal, copy and paste following commands step by step.
- **step 1** `git clone "https://github.com/Ritwikrajsingh/linux-firmware.git"`
- **step 2** `cd linux-firmware-amdgpu/i915`
- **step 3** `cp -a . /lib/firmware/i915/`
- All done.

Hope your problem is solved now.

## Currently availavle firmwares
### amdgpu
> `amur` `arcturus` `banksbanks_k_2_smc` `bonaire` `carrizo` `dimgrey_cavefish` `fiji` `green_sardine` `hainan` `kabini` `kaveri` `mullins` `navy_flounfer` `navi10` `navi12` `navi14` `oland` `picasso` `pitcairn` `polaris10` `polaris12` `raven` `raven2` `renoir` `si58_mc` `sienna_cichlid` `stoney` `tahiti` `tonga` `topaz` `vangogh` `vega10` `vega10_acg` `vega12` `vega12_gpu` `vega20` `vegam` `verde_ce`
### i915
> `adlp_dmc_ver2_12.bin`

I'll try to add other remaining firmwares ASAP.
