# lib/firmware/amdgpu
Fix for `W: Possible missing firmware /lib/firmware/amdgpu/`

### steps to fix
- Open terminal, copy and pase these commads step by step.
- **step 1** `git clone "https://github.com/Ritwikrajsingh/linux-firmware-amdgpu.git"`
- **step 2** `cd linux-firmware-amdgpu/amdgpu`
- **step 3** `cp -a . /lib/firmware/amdgpu/`
- All done.

Hope your problem is solved now.

### currently availavle firmwares

> `banksbanks_k_2_smc` `bonaire` `carrizo` `fiji` `green_sardine` `hainan` `kabini` `kaveri` `mullins` `navi10` `navi12` `navi14` `oland` `picasso` `pitcairn` `polaris10` `polaris12` `raven` `raven2` `renoir` `si58_mc` `sienna_cichlid` `stoney` `tahiti` `tonga` `topaz` `vega10` `vega10_acg` `vega12` `vega12_gpu` `vega20` `vegam` `verde_ce`

I'll try to add other remaining firmwares ASAP.