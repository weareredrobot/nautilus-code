project('nautilus-code', 'c',
  version: '0.1',
  default_options: [
    'prefix=/usr',
  ]
)

shared_module(meson.project_name(),
  ['nautilus-code-module.c', 'nautilus-code.c'],
  dependencies : dependency('libnautilus-extension'),
  install_dir: get_option('prefix') / get_option('libdir') / 'nautilus/extensions-3.0',
  install: true,
)
