project ('valascript', 'c', 'vala')

gee_dep = dependency('gee-0.8')

executable('valascript',
    'src/main.vala',
    'src/scanner.vala',
    'src/token.vala',
    'src/utils.vala',
    'src/parser.vala',
    'src/ast.vala',
    dependencies: [
        gee_dep
    ])
