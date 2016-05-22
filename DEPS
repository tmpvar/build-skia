deps = {
  "src/third_party/skia":
      "git+https://github.com/tmpvar/skia.cc.git@6e36ba7bf19cc7597837bb0416882ad4d699916b",
  "tools/gyp":
      "git+https://chromium.googlesource.com/external/gyp"
}

hooks = [
  {
    # A change to a .gyp, .gypi or to GYP itself should run the generator.
    "name": "gyp",
    "pattern": ".",
    "action": ["python", "src/bin/gyp_build_skia"]
  }
]
