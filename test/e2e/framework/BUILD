package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_binary",
    "go_library",
    "go_test",
    "cgo_library",
)

go_library(
    name = "go_default_library",
    srcs = [
        "cleanup.go",
        "exec_util.go",
        "federation_util.go",
        "framework.go",
        "gobindata_util.go",
        "kubelet_stats.go",
        "log_size_monitoring.go",
        "metrics_util.go",
        "networking_utils.go",
        "nodes_util.go",
        "perf_util.go",
        "pods.go",
        "resource_usage_gatherer.go",
        "test_context.go",
        "util.go",
    ],
    tags = ["automanaged"],
    deps = [
        "//federation/client/clientset_generated/federation_release_1_5:go_default_library",
        "//pkg/api:go_default_library",
        "//pkg/api/errors:go_default_library",
        "//pkg/api/unversioned:go_default_library",
        "//pkg/api/v1:go_default_library",
        "//pkg/api/validation:go_default_library",
        "//pkg/apimachinery/registered:go_default_library",
        "//pkg/apis/extensions:go_default_library",
        "//pkg/client/clientset_generated/internalclientset:go_default_library",
        "//pkg/client/clientset_generated/internalclientset/typed/core/internalversion:go_default_library",
        "//pkg/client/clientset_generated/release_1_5:go_default_library",
        "//pkg/client/restclient:go_default_library",
        "//pkg/client/typed/discovery:go_default_library",
        "//pkg/client/typed/dynamic:go_default_library",
        "//pkg/client/unversioned:go_default_library",
        "//pkg/client/unversioned/clientcmd:go_default_library",
        "//pkg/client/unversioned/clientcmd/api:go_default_library",
        "//pkg/client/unversioned/remotecommand:go_default_library",
        "//pkg/cloudprovider:go_default_library",
        "//pkg/cloudprovider/providers/gce:go_default_library",
        "//pkg/controller:go_default_library",
        "//pkg/controller/deployment/util:go_default_library",
        "//pkg/fields:go_default_library",
        "//pkg/kubectl:go_default_library",
        "//pkg/kubelet/api/v1alpha1/stats:go_default_library",
        "//pkg/kubelet/metrics:go_default_library",
        "//pkg/kubelet/server/remotecommand:go_default_library",
        "//pkg/kubelet/server/stats:go_default_library",
        "//pkg/kubelet/util/format:go_default_library",
        "//pkg/labels:go_default_library",
        "//pkg/master/ports:go_default_library",
        "//pkg/metrics:go_default_library",
        "//pkg/runtime:go_default_library",
        "//pkg/ssh:go_default_library",
        "//pkg/types:go_default_library",
        "//pkg/util/errors:go_default_library",
        "//pkg/util/exec:go_default_library",
        "//pkg/util/intstr:go_default_library",
        "//pkg/util/labels:go_default_library",
        "//pkg/util/rand:go_default_library",
        "//pkg/util/runtime:go_default_library",
        "//pkg/util/sets:go_default_library",
        "//pkg/util/system:go_default_library",
        "//pkg/util/uuid:go_default_library",
        "//pkg/util/validation:go_default_library",
        "//pkg/util/wait:go_default_library",
        "//pkg/util/yaml:go_default_library",
        "//pkg/version:go_default_library",
        "//pkg/watch:go_default_library",
        "//test/e2e/generated:go_default_library",
        "//test/e2e/perftype:go_default_library",
        "//test/utils:go_default_library",
        "//vendor:github.com/blang/semver",
        "//vendor:github.com/golang/glog",
        "//vendor:github.com/google/cadvisor/info/v1",
        "//vendor:github.com/onsi/ginkgo",
        "//vendor:github.com/onsi/ginkgo/config",
        "//vendor:github.com/onsi/gomega",
        "//vendor:github.com/onsi/gomega/types",
        "//vendor:github.com/prometheus/common/expfmt",
        "//vendor:github.com/prometheus/common/model",
        "//vendor:github.com/spf13/viper",
        "//vendor:golang.org/x/crypto/ssh",
        "//vendor:golang.org/x/net/websocket",
        "//vendor:gopkg.in/yaml.v2",
        "//vendor:k8s.io/client-go/kubernetes",
        "//vendor:k8s.io/client-go/pkg/util/sets",
        "//vendor:k8s.io/client-go/rest",
    ],
)
