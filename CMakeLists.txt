# 4-track-toy-piano-plugin — distributable product (VST3 / AU / Standalone).
#
# A thin wrapper over dehli-musikk-sampler-engine: this file states ONLY the product
# identity. Everything else (entry point, asset embed, sample-pack install, custom
# standalone, packaging metadata) comes from dmse_add_plugin — see
# dehli-musikk-sampler-engine/cmake/DmsePlugin.cmake.

dmse_add_plugin(FourTrackToyPiano
    PRODUCT_NAME "4-track Toy Piano"
    PLUGIN_CODE  Tp4t
    VERSION      2.0.0
)
