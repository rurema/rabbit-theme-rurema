require "rabbit/task/theme"

# Edit ./config.yaml to customize meta data

spec = nil
Rabbit::Task::Theme.new do |task|
  task.spec.licenses = ["GPLv3+", "CC BY-SA 3.0"]
  task.spec.files = %w[README.rd Rakefile config.yaml property.rb theme.rb]
  task.spec.files += ["data/close-quote-blue.png", "data/open-quote-blue.png"]
  spec = task.spec
end
