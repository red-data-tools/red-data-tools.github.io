# -*- ruby -*-
#
# Copyright (C) 2017-2020  Red Data Tools
#
# This program is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation, either version 3 of the License, or
# (at your option) any later version.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program.  If not, see <http://www.gnu.org/licenses/>.

require "bundler/setup"
require "jekyll/task/i18n"

Jekyll::Task::I18n.define do |task|
  task.locales = ["ja"]
  task.files = Rake::FileList["**/*.md"]
  task.files -= Rake::FileList["_*/**/*.md"]
  task.files -= Rake::FileList["README.md"]
  task.locales.each do |locale|
    task.files -= Rake::FileList["#{locale}/**/*.md"]
  end
end

task :default => ["jekyll:i18n:translate"]
