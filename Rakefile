rule '.rb' => '.y' do |t|
   sh "racc -o #{t.name} #{t.source}"
end

desc 'Build the parser'
task default: ['lib/yars/parser.rb']
