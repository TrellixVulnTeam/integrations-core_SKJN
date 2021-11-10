# CHANGELOG - Cilium

## 1.8.0 / 2021-10-04 / Agent 7.32.0

* [Added] Add HTTP option to control the size of streaming responses. See [#10183](https://github.com/DataDog/integrations-core/pull/10183).
* [Added] Add allow_redirect option. See [#10160](https://github.com/DataDog/integrations-core/pull/10160).
* [Added] Allow Kubernetes port forwarding to support any resource. See [#10127](https://github.com/DataDog/integrations-core/pull/10127).
* [Fixed] Fix the description of the `allow_redirects` HTTP option. See [#10195](https://github.com/DataDog/integrations-core/pull/10195).

## 1.7.2 / 2021-08-22 / Agent 7.31.0

* [Fixed] Re-revert cilium AD change. See [#9901](https://github.com/DataDog/integrations-core/pull/9901).

## 1.7.1 / 2021-07-13 / Agent 7.30.0

* [Fixed] Revert cilium AD change. See [#9683](https://github.com/DataDog/integrations-core/pull/9683).

## 1.7.0 / 2021-07-12

* [Added] Update container identifier. See [#9512](https://github.com/DataDog/integrations-core/pull/9512).
* [Fixed] Use cilium-agent and cilium as autodiscover identifiers. See [#9518](https://github.com/DataDog/integrations-core/pull/9518).

## 1.6.0 / 2021-05-28 / Agent 7.29.0

* [Added] Support "ignore_tags" configuration. See [#9392](https://github.com/DataDog/integrations-core/pull/9392).

## 1.5.3 / 2021-03-07 / Agent 7.27.0

* [Fixed] Rename config spec example consumer option `default` to `display_default`. See [#8593](https://github.com/DataDog/integrations-core/pull/8593).

## 1.5.2 / 2021-01-25 / Agent 7.26.0

* [Fixed] Update prometheus_metrics_prefix documentation. See [#8236](https://github.com/DataDog/integrations-core/pull/8236).

## 1.5.1 / 2020-12-11 / Agent 7.25.0

* [Fixed] Fix openmetrics integrations config specs. See [#8000](https://github.com/DataDog/integrations-core/pull/8000).

## 1.5.0 / 2020-10-31 / Agent 7.24.0

* [Added] Sync openmetrics config specs with new option ignore_metrics_by_labels. See [#7823](https://github.com/DataDog/integrations-core/pull/7823).
* [Added] Add ability to dynamically get authentication information. See [#7660](https://github.com/DataDog/integrations-core/pull/7660).

## 1.4.0 / 2020-09-21 / Agent 7.23.0

* [Added] Add RequestsWrapper option to support UTF-8 for basic auth. See [#7441](https://github.com/DataDog/integrations-core/pull/7441).
* [Fixed] Do not render null defaults for config spec example consumer. See [#7503](https://github.com/DataDog/integrations-core/pull/7503).
* [Fixed] Update proxy section in conf.yaml. See [#7336](https://github.com/DataDog/integrations-core/pull/7336).

## 1.3.0 / 2020-08-10 / Agent 7.22.0

* [Added] Add config specs. See [#7319](https://github.com/DataDog/integrations-core/pull/7319).

## 1.2.0 / 2020-05-17 / Agent 7.20.0

* [Added] Add environment runner for Kubernetes' `kind`. See [#6522](https://github.com/DataDog/integrations-core/pull/6522).
* [Added] Allow optional dependency installation for all checks. See [#6589](https://github.com/DataDog/integrations-core/pull/6589).

## 1.1.0 / 2020-04-04 / Agent 7.19.0

* [Added] Add Cilium version metadata. See [#5408](https://github.com/DataDog/integrations-core/pull/5408).
* [Fixed] Update deprecated imports. See [#6088](https://github.com/DataDog/integrations-core/pull/6088).

## 1.0.2 / 2020-01-13 / Agent 7.17.0

* [Fixed] Remove unused variables. See [#5173](https://github.com/DataDog/integrations-core/pull/5173).

## 1.0.1 / 2019-12-06 / Agent 7.16.1

* [Fixed] Raise configuration errors. See [#5163](https://github.com/DataDog/integrations-core/pull/5163).

## 1.0.0 / 2019-11-19

* [Added] New Integration: Cilium. See [#4665](https://github.com/DataDog/integrations-core/pull/4665).