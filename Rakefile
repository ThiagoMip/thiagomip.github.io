namespace :build do
task :pdf do
`bundle exec asciidoctor-pdf -apdf-style=themes/custom-theme.yml -a pdf-fontsdir=themes/fonts Curriculo_ThiagoPrieto.adoc -o docs/Curriculo_ThiagoPrieto.pdf`
end
task :html do
`bundle exec asciidoctor Curriculo_ThiagoPrieto.adoc -o docs/Curriculo_ThiagoPrieto.html`
end
end
desc 'Build all default formats'
task :build => [ 'build:html', 'build:pdf' ]
