namespace :config do
  desc 'Setup i3 configuration'
  task i3: ['link:rofi', 'link:i3']
end

namespace :link do
  task :i3 do
    target_file = "#{ENV['HOME']}/.config/i3"
    rm_rf target_file if File.exist?(target_file)
    cmd = "ln -s #{pwd}/i3 #{ENV['HOME']}/.config/i3"
    sh cmd
  end

  task :rofi do
    target_file = "#{ENV['HOME']}/.config/rofi"
    rm_rf target_file if File.exist?(target_file)
    cmd = "ln -s #{pwd}/rofi #{ENV['HOME']}/.config/rofi"
    sh cmd
  end
end
