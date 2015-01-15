desc "build the pdf"
task :default => [] do
  sh "pdflatex commands.tex"
  sh "pdflatex commands.tex"
  sh "bibtex commands"
  sh "bibtex commands"
  sh "pdflatex commands.tex"
  sh "pdflatex commands.tex"
end


task :clean do
  sh "rm -rf *.aux *.bbl *.blg *.log"
end
