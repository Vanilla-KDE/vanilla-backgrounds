project('vanilla-backgrounds',
  meson_version: '>= 0.50.0'
)

wallpapers = [
  'fairy-tale',
  'impellent',
  'orchid',
  'petals',
  'petals-soft',
  'soft-neon',
  'vanilla',
]

foreach wp : wallpapers
  install_subdir('backgrounds' / wp, install_dir: get_option('datadir') / 'wallpapers')
endforeach