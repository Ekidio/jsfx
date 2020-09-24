# jsfx
A free collection of JS (JesuSonic) plugins for [Reaper](https://www.reaper.fm/).

_See the source files for details and instructions._

#### Quick Links
[Effects](#effects)<br>
[Installation](#installation)<br>
[Support](#support)

<a name="effects"></a>
## Effects

| Screenshot | Plugin | Description |
| ---------- | ------ | ----------- |
| [![amp_sim](https://user-images.githubusercontent.com/53377392/93859320-cc032c80-fcbd-11ea-9a05-22c54dcf73a6.jpg)](https://user-images.githubusercontent.com/53377392/93859396-e0dfc000-fcbd-11ea-85ea-eb3b09e0116e.png) | [Amp Sim](https://github.com/chkhld/jsfx/blob/master/plugins/amp_sim.jsfx) | Guitar and bass amplifier with up to 16x oversampling, mono/stereo routings, pre/post/triggered noise gate, booster pedal function, interactive inter-stage EQ bands, dynamic Depth and Presence bands, and maximizer circuit. |
| [![bus_comp](https://user-images.githubusercontent.com/53377392/93859322-cc9bc300-fcbd-11ea-8795-d69592e8141c.jpg)](https://user-images.githubusercontent.com/53377392/93859401-e3421a00-fcbd-11ea-8056-9d033e4af5bb.png) | [Bus Comp](https://github.com/chkhld/jsfx/blob/master/plugins/bus_comp.jsfx) | Submix bus oriented compressor with automatic/program-dependent release, fadeable stereo linking, Mid/Side mode, external sidechain input with high pass filter, instability noise, dynamic saturation, optional output hard clipping and dry/wet mix for parallel compression. |
| [![cab_sim](https://user-images.githubusercontent.com/53377392/93859324-cd345980-fcbd-11ea-8504-c00930c5cb2b.jpg)](https://user-images.githubusercontent.com/53377392/93859404-e4734700-fcbd-11ea-927b-15506aa187e6.png) | [Cabinet Sim](https://github.com/chkhld/jsfx/blob/master/plugins/cabinet_sim.jsfx) | Simple cab sim with 5 burnt-in impulse responses, 4 for guitar and 1 for bass. Can **not** load IRs from file. |
| [![consolidator](https://user-images.githubusercontent.com/53377392/93859325-cd345980-fcbd-11ea-94d2-1d58e0269c98.jpg)](https://user-images.githubusercontent.com/53377392/93859406-e50bdd80-fcbd-11ea-8b9f-396c628e94d6.png) | [Consolidator](https://github.com/chkhld/jsfx/blob/master/plugins/consolidator.jsfx) | A set of 3 compressors with sidechain filter and stereo linking chained in a row, each with its own character. Has a dry/wet mix parameter for instant parallel/NY compression and Mid/Side mode. |
| [![correlation_meter](https://user-images.githubusercontent.com/53377392/93859326-cdccf000-fcbd-11ea-9f22-8a567230523b.jpg)](https://user-images.githubusercontent.com/53377392/93859409-e5a47400-fcbd-11ea-9ce7-8d7cdc129304.png) | [Correlation Meter](https://github.com/chkhld/jsfx/blob/master/plugins/correlation_meter.jsfx) | Inspect your song's stereo phase balance and find mono-problematic areas by watching an indicator go red. |
| [![dc_offset](https://user-images.githubusercontent.com/53377392/93859327-cdccf000-fcbd-11ea-80a2-8ae9dae9b487.jpg)](https://user-images.githubusercontent.com/53377392/93859412-e5a47400-fcbd-11ea-91a9-ead68e5387f1.png) | [DC Offset](https://github.com/chkhld/jsfx/blob/master/plugins/dc_offset.jsfx) | Adds constant 0 Hz content and shifts waveforms up or down, probably only useful to test DC filters. |
| [![eq_560](https://user-images.githubusercontent.com/53377392/93904972-b6f8be80-fcfa-11ea-8443-a229398ded41.jpg)](https://user-images.githubusercontent.com/53377392/93904708-6bdeab80-fcfa-11ea-855e-d74acb5bd074.png) | [EQ 560](https://github.com/chkhld/jsfx/blob/master/plugins/eq_560.jsfx) | Classic American 10-band graphic console equalizer. Limited flexibility, fast and streamlined workflow. Uses 2x oversampling for accurate high frequency filter curves, adds some character. |
| [![filthy_delay](https://user-images.githubusercontent.com/53377392/93859329-ce658680-fcbd-11ea-87ed-fa3d0e0debe4.jpg)](https://user-images.githubusercontent.com/53377392/93859414-e63d0a80-fcbd-11ea-8141-5a6bb04e032d.png) | [Filthy Delay](https://github.com/chkhld/jsfx/blob/master/plugins/filthy_delay.jsfx) | Stereo delay with multiple routings (stereo, inverted, ping-pong, mono, more to come), plus optional filters, boostable saturation and downsampling degradation in the feedback path. |
| [![foldback_distortion](https://user-images.githubusercontent.com/53377392/93859331-ce658680-fcbd-11ea-9240-b1e8d81e14f8.jpg)](https://user-images.githubusercontent.com/53377392/93859419-e76e3780-fcbd-11ea-9a3f-bac70377edec.png) | [Foldback Distortion](https://github.com/chkhld/jsfx/blob/master/plugins/foldback_distortion.jsfx) | Folds waves between 0 and an adjustable ceiling, very harsh and nasty distortion. |
| [![gate_expander](https://user-images.githubusercontent.com/53377392/93859332-cefe1d00-fcbd-11ea-92be-18f97e3a6d7f.jpg)](https://user-images.githubusercontent.com/53377392/93859427-e806ce00-fcbd-11ea-9b08-9125e0add949.png) | [Gate/Expander](https://github.com/chkhld/jsfx/blob/master/plugins/gate_expander.jsfx) | Several channel routings, external sidechain, sidechain filter, fadeable stereo linking, hysteresis, and it can be switched between gate (fades to silence) and expander (fades to defined volume) modes. |
| [![hard_clipper](https://user-images.githubusercontent.com/53377392/93859333-cefe1d00-fcbd-11ea-82c1-9239de78b162.jpg)](https://user-images.githubusercontent.com/53377392/93859429-e89f6480-fcbd-11ea-9d21-6f378410dcd7.png) | [Hard Clipper](https://github.com/chkhld/jsfx/blob/master/plugins/hard_clipper.jsfx) | Simple and effective, chops away peaks above an adjustable ceiling volume, call it cold transistor distortion if you must. |
| [![impulse_generator](https://user-images.githubusercontent.com/53377392/93859334-cf96b380-fcbd-11ea-82b9-51c37f16f42f.jpg)](https://user-images.githubusercontent.com/53377392/93859431-e89f6480-fcbd-11ea-9455-53d91c143f03.png) | [Impulse Generator](https://github.com/chkhld/jsfx/blob/master/plugins/impulse_generator.jsfx) | Generates a 1-sample impulse when triggered, for use when sampling devices to IRs. |
| [![interpolated_noise](https://user-images.githubusercontent.com/53377392/93859336-cf96b380-fcbd-11ea-9b8e-24a5dfb002be.jpg)](https://user-images.githubusercontent.com/53377392/93859432-e937fb00-fcbd-11ea-8389-fd8ca945ee03.png) | [Interpolated Noise](https://github.com/chkhld/jsfx/blob/master/plugins/interpolated_noise.jsfx) | Various flavours of pleasingly natural and organically chaotic noise created with the help of various interpolation methods. |
| [![m-s_fader](https://user-images.githubusercontent.com/53377392/93859337-d02f4a00-fcbd-11ea-9455-9bb28fdfc63e.jpg)](https://user-images.githubusercontent.com/53377392/93859434-e937fb00-fcbd-11ea-81e5-b51d3218eab1.png) | [M-S Fader](https://github.com/chkhld/jsfx/blob/master/plugins/m-s_fader.jsfx) | Converts a stereo source to a Mid/Side signal and then fades between 100% Mid and 100% Side signal, or a mix of both. Great to remove the center signal, or to focus in on it. |
| [![phase_scope](https://user-images.githubusercontent.com/53377392/93859338-d02f4a00-fcbd-11ea-8eb7-362d9b0df257.jpg)](https://user-images.githubusercontent.com/53377392/93859438-e9d09180-fcbd-11ea-8515-8df9d63c0fe0.png) | [Phase Scope](https://github.com/chkhld/jsfx/blob/master/plugins/phase_scope.jsfx) | Visualizes the stereo field of a signal, also commonly known as Goniometer, Vector Scope or Lissajous. Selectable visualization colour and optional freeze-on-pause function. |
| [![reference_noise](https://user-images.githubusercontent.com/53377392/93859339-d02f4a00-fcbd-11ea-9dc8-ef5bf0e0c1e4.jpg)](https://user-images.githubusercontent.com/53377392/93859440-ea692800-fcbd-11ea-8bba-a910dfb57fa2.png) | [Reference Noise](https://github.com/chkhld/jsfx/blob/master/plugins/reference_noise.jsfx) | Provides various noise profiles, filtered or plain, to use as target reference for spectral/visual mixing. |
| [![signal_crusher](https://user-images.githubusercontent.com/53377392/93859341-d0c7e080-fcbd-11ea-9d88-f074e400a7b1.jpg)](https://user-images.githubusercontent.com/53377392/93859442-eb01be80-fcbd-11ea-9ff8-6d0f82675954.png) | [Signal Crusher](https://github.com/chkhld/jsfx/blob/master/plugins/signal_crusher.jsfx) | Sample rate changes, lost sample reconstruction, bit truncation, bit dithering... it's all in here. |
| [![soft_clipper](https://user-images.githubusercontent.com/53377392/93859342-d1607700-fcbd-11ea-83d0-5e1ed273bcf6.jpg)](https://user-images.githubusercontent.com/53377392/93859447-eb01be80-fcbd-11ea-8964-34d06c1eff2a.png) | [Soft Clipper](https://github.com/chkhld/jsfx/blob/master/plugins/soft_clipper.jsfx) | Increasingly lowers signal peaks the closer they get to an adjustable ceiling volume, call it warm tube overdrive if you must. Has up to 16x oversampling, DC blocker and optional final (non oversampled) hard clipping stage for true 0 dBfs output. |
| [![stereo_bleed_remover](https://user-images.githubusercontent.com/53377392/93859344-d1607700-fcbd-11ea-8285-5eb93eab6a0b.jpg)](https://user-images.githubusercontent.com/53377392/93859448-eb9a5500-fcbd-11ea-91b0-ffe75ae5e346.png) | [Stereo Bleed Remover](https://github.com/chkhld/jsfx/blob/master/plugins/stereo_bleed_remover.jsfx) | An attempt at removing unwanted bleed between channels in a stereo signal. |
| [![stereo_pan](https://user-images.githubusercontent.com/53377392/93859348-d1f90d80-fcbd-11ea-85b2-ff14ff8d8040.jpg)](https://user-images.githubusercontent.com/53377392/93859449-ec32eb80-fcbd-11ea-97bb-358fd0e5a852.png) | [Stereo Pan](https://github.com/chkhld/jsfx/blob/master/plugins/stereo_pan.jsfx) | Utility that implements various standardized pan laws, as well as some custom methods by me. |
| [![telephone](https://user-images.githubusercontent.com/53377392/93859349-d291a400-fcbd-11ea-8c5b-ea25daec05f2.jpg)](https://user-images.githubusercontent.com/53377392/93859450-eccb8200-fcbd-11ea-9949-20ed0b629db2.png) | [Telephone](https://github.com/chkhld/jsfx/blob/master/plugins/telephone.jsfx) | Makes vocals sound like they're coming through a phone receiver, also worth slamming on drums. |
| [![test_signals](https://user-images.githubusercontent.com/53377392/93859354-d291a400-fcbd-11ea-9055-98d1ff9f444b.jpg)](https://user-images.githubusercontent.com/53377392/93859452-ed641880-fcbd-11ea-97ea-6551bfddb1cd.png) | [Test Signals](https://github.com/chkhld/jsfx/blob/master/plugins/test_signals.jsfx) | A collection of 13 different test tone and noise generators in one plugin, 14 if you count silence. Can have a different generator on each channel, can output both or just one channel, can sum both channels. |
| [![track_comp](https://user-images.githubusercontent.com/53377392/93859355-d32a3a80-fcbd-11ea-9d02-4a2ebd12b61a.jpg)](https://user-images.githubusercontent.com/53377392/93859456-ee954580-fcbd-11ea-9354-7b8abc7c1a73.png) | [Track Comp](https://github.com/chkhld/jsfx/blob/master/plugins/track_comp.jsfx) | A low-CPU and ultra-flexible compressor, with everything from peak/RMS detection over feed-forward/-back modes, stereo linking and channel setups to automatic gain compensation and dynamic saturation. |
| [![volume_range_trim](https://user-images.githubusercontent.com/53377392/93859356-d32a3a80-fcbd-11ea-8c63-8d43c479ae6c.jpg)](https://user-images.githubusercontent.com/53377392/93859459-efc67280-fcbd-11ea-8b01-92dabd32d2d2.png) | [Volume Range Trim](https://github.com/chkhld/jsfx/blob/master/plugins/volume_range_trim.jsfx) | Fader to non-destructively alter a signal's volume within a specific range (+/- 6, 12, 24, 48 dB), gives finer control when automating volume. Auto-adapts to track's channel count. |
| [![volume_trim](https://user-images.githubusercontent.com/53377392/93859358-d3c2d100-fcbd-11ea-8ad8-65c930b86da4.jpg)](https://user-images.githubusercontent.com/53377392/93859462-f05f0900-fcbd-11ea-8deb-3fb005a5e5b4.png) | [Volume Trim](https://github.com/chkhld/jsfx/blob/master/plugins/volume_trim.jsfx) | Simple fader to alter a signal's volume, useful for gain-staging between plugins. Auto-adapts to track's channel count. |
| [![wave_scope](https://user-images.githubusercontent.com/53377392/93859359-d3c2d100-fcbd-11ea-98cb-7922bf3ec924.jpg)](https://user-images.githubusercontent.com/53377392/93859464-f05f0900-fcbd-11ea-8de7-da487734c2b7.png) | [Wave Scope](https://github.com/chkhld/jsfx/blob/master/plugins/wave_scope.jsfx) | Waveform display that can visualize various mono/stereo channel streams as Decibels, signed or absolute samples. With fadeable colours and freeze-on-pause function. |



_(There may be more in the future)_

<a name="installation"></a>
## Installation
- The important stuff is in the [plugins](https://github.com/chkhld/jsfx/blob/master/plugins/) folder, so download what you want from there, or [get the full release here](https://github.com/chkhld/jsfx/releases/).
- If you don't know what to do with these files, watch the [Reaper Blog tutorial](https://reaperblog.net/2015/06/quick-tip-how-to-install-js-plugins/) on how to install JS plugins.

<a name="support"></a>
## Support
This is just a fun project for me, I do this on the side to waste time or template C++ code, so don't expect too much of an effort. But if you find any bugs, or if you have any suggestions for improvements, feel free to report them in the [issue tracker](https://github.com/chkhld/jsfx/issues), I'll have a look there every now and then.

Have fun! <3
