### pytestAPI-chinese

pytest最新版本([5.4.2](pytestAPI-chinese))的API的翻译与详解，此项目只做API的详解，翻译时共有以下78个APL：

- Functions
	- [pytest.approx](https://docs.pytest.org/en/5.4.2/reference.html#pytest-approx)
	- [pytest.fail](https://docs.pytest.org/en/5.4.2/reference.html#pytest-fail)
	- [pytest.skip](https://docs.pytest.org/en/5.4.2/reference.html#pytest-skip)
	- [pytest.importorskip](https://docs.pytest.org/en/5.4.2/reference.html#pytest-importorskip)
	- [pytest.xfail](https://docs.pytest.org/en/5.4.2/reference.html#pytest-xfail)
	- [pytest.exit](https://docs.pytest.org/en/5.4.2/reference.html#pytest-exit)
	- [pytest.main](https://docs.pytest.org/en/5.4.2/reference.html#pytest-main)
	- [pytest.param](https://docs.pytest.org/en/5.4.2/reference.html#pytest-param)
	- [pytest.raises](https://docs.pytest.org/en/5.4.2/reference.html#pytest-raises)
	- [pytest.deprecated_call](https://docs.pytest.org/en/5.4.2/reference.html#pytest-deprecated-call)
	- [pytest.register_assert_rewrite](https://docs.pytest.org/en/5.4.2/reference.html#pytest-register-assert-rewrite)
	- [pytest.warns](https://docs.pytest.org/en/5.4.2/reference.html#pytest-warns)
	- [pytest.freeze_includes](https://docs.pytest.org/en/5.4.2/reference.html#pytest-freeze-includes)
- Marks
	- [pytest.mark.filterwarnings](https://docs.pytest.org/en/5.4.2/reference.html#pytest-mark-filterwarnings)
	- [pytest.mark.parametrize](https://docs.pytest.org/en/5.4.2/reference.html#pytest-mark-parametrize)
	- [pytest.mark.skip](https://docs.pytest.org/en/5.4.2/reference.html#pytest-mark-skip)
	- [pytest.mark.skipif](https://docs.pytest.org/en/5.4.2/reference.html#pytest-mark-skipif)
	- [pytest.mark.usefixtures](https://docs.pytest.org/en/5.4.2/reference.html#pytest-mark-usefixtures)
	- [pytest.mark.xfail](https://docs.pytest.org/en/5.4.2/reference.html#pytest-mark-xfail)
	- [custom marks](https://docs.pytest.org/en/5.4.2/reference.html#custom-marks)
- Fixtures
	- [@pytest.fixture](https://docs.pytest.org/en/5.4.2/reference.html#pytest-fixture)
	- [config.cache](https://docs.pytest.org/en/5.4.2/reference.html#config-cache)
	- [capsys](https://docs.pytest.org/en/5.4.2/reference.html#capsys)
	- [capsysbinary](https://docs.pytest.org/en/5.4.2/reference.html#capsysbinary)
	- [capfd](https://docs.pytest.org/en/5.4.2/reference.html#capfd)
	- [capfdbinary](https://docs.pytest.org/en/5.4.2/reference.html#capfdbinary)
	- [doctest_namespace](https://docs.pytest.org/en/5.4.2/reference.html#doctest-namespace)
	- [request](https://docs.pytest.org/en/5.4.2/reference.html#request)
	- [pytestconfig](https://docs.pytest.org/en/5.4.2/reference.html#pytestconfig)
	- [record_property](https://docs.pytest.org/en/5.4.2/reference.html#record-property)
	- [record_testsuite_property](https://docs.pytest.org/en/5.4.2/reference.html#record-testsuite-property)
	- [caplog](https://docs.pytest.org/en/5.4.2/reference.html#caplog)
	- [monkeypatch](https://docs.pytest.org/en/5.4.2/reference.html#monkeypatch)
	- [testdir](https://docs.pytest.org/en/5.4.2/reference.html#testdir)
	- [recwarn](https://docs.pytest.org/en/5.4.2/reference.html#recwarn)
	- [tmp_path](https://docs.pytest.org/en/5.4.2/reference.html#tmp-path)
	- [tmp_path_factory](https://docs.pytest.org/en/5.4.2/reference.html#tmp-path-factory)
	- [tmpdir](https://docs.pytest.org/en/5.4.2/reference.html#tmpdir)
	- [tmpdir_factory](https://docs.pytest.org/en/5.4.2/reference.html#tmpdir-factory)
- Hooks
	- [Bootstrapping hooks](https://docs.pytest.org/en/5.4.2/reference.html#bootstrapping-hooks)
	- [Initialization hooks](https://docs.pytest.org/en/5.4.2/reference.html#initialization-hooks)
	- [Test running hooks](https://docs.pytest.org/en/5.4.2/reference.html#test-running-hooks)
	- [Collection hooks](https://docs.pytest.org/en/5.4.2/reference.html#collection-hooks)
	- [Reporting hooks](https://docs.pytest.org/en/5.4.2/reference.html#reporting-hooks)
	- [Debugging/Interaction hooks](https://docs.pytest.org/en/5.4.2/reference.html#debugging-interaction-hooks)
- Objects
	- [CallInfo](https://docs.pytest.org/en/5.4.2/reference.html#callinfo)
	- [Class](https://docs.pytest.org/en/5.4.2/reference.html#class)
	- [Collector](https://docs.pytest.org/en/5.4.2/reference.html#collector)
	- [Config](https://docs.pytest.org/en/5.4.2/reference.html#config)
	- [ExceptionInfo](https://docs.pytest.org/en/5.4.2/reference.html#exceptioninfo)
	- [pytest.ExitCode](https://docs.pytest.org/en/5.4.2/reference.html#pytest-exitcode)
	- [FixtureDef](https://docs.pytest.org/en/5.4.2/reference.html#fixturedef)
	- [FSCollector](https://docs.pytest.org/en/5.4.2/reference.html#fscollector)
	- [Function](https://docs.pytest.org/en/5.4.2/reference.html#function)
	- [Item](https://docs.pytest.org/en/5.4.2/reference.html#item)
	- [MarkDecorator](https://docs.pytest.org/en/5.4.2/reference.html#markdecorator)
	- [MarkGenerator](https://docs.pytest.org/en/5.4.2/reference.html#markgenerator)
	- [Mark](https://docs.pytest.org/en/5.4.2/reference.html#mark)
	- [Metafunc](https://docs.pytest.org/en/5.4.2/reference.html#metafunc)
	- [Module](https://docs.pytest.org/en/5.4.2/reference.html#module)
	- [Node](https://docs.pytest.org/en/5.4.2/reference.html#node)
	- [Parser](https://docs.pytest.org/en/5.4.2/reference.html#parser)
	- [PluginManager](https://docs.pytest.org/en/5.4.2/reference.html#pluginmanager)
	- [PytestPluginManager](https://docs.pytest.org/en/5.4.2/reference.html#pytestpluginmanager)
	- [Session](https://docs.pytest.org/en/5.4.2/reference.html#session)
	- [TestReport](https://docs.pytest.org/en/5.4.2/reference.html#testreport)
	- [_Result](https://docs.pytest.org/en/5.4.2/reference.html#result)
- Special Variables
	- [collect_ignore](https://docs.pytest.org/en/5.4.2/reference.html#collect-ignore)
	- [collect_ignore_glob](https://docs.pytest.org/en/5.4.2/reference.html#collect-ignore-glob)
	- [pytest_plugins](https://docs.pytest.org/en/5.4.2/reference.html#pytest-plugins)
	- [pytestmark](https://docs.pytest.org/en/5.4.2/reference.html#pytestmark)
	- [PYTEST_DONT_REWRITE (module docstring)](https://docs.pytest.org/en/5.4.2/reference.html#pytest-dont-rewrite-module-docstring)
- Environment Variables
	- [PYTEST_ADDOPTS](https://docs.pytest.org/en/5.4.2/reference.html#pytest-addopts)
	- [PYTEST_DEBUG](https://docs.pytest.org/en/5.4.2/reference.html#pytest-debug)
	- [PYTEST_PLUGINS](https://docs.pytest.org/en/5.4.2/reference.html#id9)
	- [PYTEST_DISABLE_PLUGIN_AUTOLOAD](https://docs.pytest.org/en/5.4.2/reference.html#pytest-disable-plugin-autoload)
	- [PYTEST_CURRENT_TEST](https://docs.pytest.org/en/5.4.2/reference.html#pytest-current-test)
- Exceptions
	- [UsageError](https://docs.pytest.org/en/5.4.2/reference.html#usageerror)
- [Configuration Options](https://docs.pytest.org/en/5.4.2/reference.html#configuration-options)

因为笔者的时间有限，都是在工作之余完成，保证一天最少翻译一个API，计划全项目两个月完成。后续版本有更新也会随着更正

#### 环境

`python:3.8.2`

`pytest:5.4.2`

