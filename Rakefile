task :eslint do
  system "../../node_modules/.bin/eslint lib/*.js"
end

task :webpack do
  system "~/code/${GITHUB_USERNAME}/fullstack-challenges/04-Front-End/node_modules/.bin/webpack-dev-server"
end

task default: [:eslint]
