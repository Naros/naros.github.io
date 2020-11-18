$use_bundle_exec = true
$awestruct_cmd = nil
$antora_config = "playbook.yml"
task :default => :build

desc 'Performs the website build'
task :build do
  msg 'Rake build called'
  exit 0
end

# Print a message to STDOUT
def msg(text, level = :info)
  case level
  when :warn
    puts "\e[31m#{text}\e[0m"
  else
    puts "\e[33m#{text}\e[0m"
  end
end
