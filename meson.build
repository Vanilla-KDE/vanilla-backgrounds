project('vanilla-backgrounds',
  meson_version: '>= 0.50.0'
)

wallpapers = [
  'FairyTale',
  'Impellent',
  'Orchid',
  'Petals',
  'PetalsSoft',
  'SoftNeon',
  'Vanilla',
]

foreach wp : wallpapers
  install_subdir('backgrounds' / wp, install_dir: get_option('datadir') / 'wallpapers')
endforeach