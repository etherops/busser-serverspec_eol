# <a name="title"></a> THIS IS A FORK
Forked from [busser-serverspec][https://github.com/test-kitchen/busser-serverspec@0.5.10]


# <a name="title"></a> Busser::RunnerPlugin::Serverspec

A Busser runner plugin for Serverspec for EOL Ruby versions < 2.3 

## <a name="installation"></a> Installation and Setup

Please read the Busser [plugin usage][plugin_usage] page for more details.

## <a name="usage"></a> Usage

Please put test files into [COOKBOOK]/test/integration/[SUITES]/serverspec_eol/

```cookbook
`-- test
    `-- integration
        `-- default
            `-- serverspec_eol
                |-- Gemfile
                |-- localhost
                |   `-- httpd_spec.rb
                `-- spec_helper.rb
```

`Gemfile` is optional. You can specify installing Serverspec version and install gems you need.
