# frozen_string_literal: true

source "https://rubygems.org"

gemspec

# rubocop:disable Bundler/OrderedGems
gem "cassandra-cql", "1.2.3", github: "kreynolds/cassandra-cql", ref: "02b5abbe441a345c051a180327932566fd66bb36"
  gem "thrift_client", # rubocop:disable Layout/IndentationConsistency
      "0.9.3",
      require: false,
      github: "twitter/thrift_client",
      ref: "5c10d59881825cb8e26ab1aa8f1d2738e88c0e83"
gem "config_file", path: "../config_file"
gem "sidhant"
gem 'Sidhant_apeli', '31.6.2'
# rubocop:enable Bundler/OrderedGems

eval_gemfile("../gemfile_prefix.rb")
