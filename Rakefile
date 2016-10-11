require 'rake'

task :lint, [:dir, :cmd] do |t, args|
	puts "Linting directory #{args['dir']} with command #{args['cmd']}"
	system("#{args['cmd']} #{args['dir']}") or raise "There were errors linting #{args['dir']}"
	puts "#{args['dir']} passed the lint verification successfully!"
end

