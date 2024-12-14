GoalKeeper is a command line interface application for tracking goals.
A CS50x 2024 final project

Sketch Miner Process Maps of the solution:

- [View Goals](https://www.bpmn-sketch-miner.ai/#EYBwNgdgXAbgjAKALRIQVQM4FMBOUEBqAllgO4AEAtgJ7kDmA9gIZgYID075GALkzwFcM5IsIDkDCOR44mAYwDWY8kwgATchIBmW6bMVjCJCjXrNW3PoLbEyZluTVY+RVkA)
- [Create New Goals and KPIs](https://www.bpmn-sketch-miner.ai/#EYBwNgdgXAbgjAKALRIQVQM4FMBOUAECAwjlgIYAuW+EWA7vgOYD2ZYxpl1Lb+FAlhTBYO5Kk1Zh8AEywYAxjn4gBzCKK4TeFMjkZYK+ZgFcK85gFsRJMd0l9d+w9K4IAymRjVmOGVmHiPOxuAJ4YVBYEAAq4AGY+FvhuAHQAsskAgskASskAKvhkGNjFVhAUCAD0lfgA8hDy1BQAFtS0DEH4zUX4wFhYEPgYnljSADR8rfjG2L50-GBS3V6T1GTAC4IhfMz4YPwQANZGtEa+Fj7UANJRAJIYO6ta7AAyB8ft+De3j0Ea4t8+IJhP9rnc-AolCp+GoqjVAVYKEp5A9zMYwNJemt8CBcI1yhMDlR9DgJrEwKwKBN5MYcKQGttpMxFroJnQsPxGM0KjZNAiDMi+CFcaDCjR6PgaeFLF9wYjBRRhdZOADwTo9AYZK5qvgAELMZnkQbyVryY7AZgAD3cuPk-Fi2zorRauFlPwwzRMGKx+FIIB8VExal9WEY6N0YBCCHuIf9OAEEEYIYAjsZ+KRpAB+BDZLBxhNJiDMQykVPp0YIdCzAiiz5-XmBewCITK2zPCGKZSqdQNuzaRyakxmSytzSddVOLVUdwjM5+AJ94JhCLROIJJJpTI5fKFYpyDBlCo6+qNJ51+zdB59AZDEbjJ4zV3zRZdWcuwobfaKx77I4nbznJcboPBQuzvn8bx-p8gKgc8oowcCo6qj8siQl2MLqDq-JIvwKKSl6mJ9GKuI4PiVL4ESoa4GSFKUNStL0vIjLMmArL4OynLcvBcoCrhQoir2YqfFKoGJNhCpKtxPwTpqLjTjq+qGmQxqmuaVo2lgdoOuxzqtL4gIegRPp+gGownCGYasTgkbRg8JnxgcSalmmGbZrm+aORRdlYGWGZwvg7kBp58hkLIDTUCFgxEeyWCHJGEwXOUzTxfgqa6FQ1lRoJ9kFpKoUDI0CAACJYLEBxrIwpBmYClD4OQJqxkFiY4swRL+ZB5CknszBJgY8jFaV5U4jgzAAFaaYGjUOc1-ptaE4RYJE+BRCN43yIYZCVf0mI1YY9XNFNuWzeUCAABQCFYOAAJToCAclgj8tUKK00jomZOXuAMO3gh9laYLgNaCeebCiuOiGg-YqGdtCsKCeOA6GEO5hWBD-Yas4rgeCsPjzgYi7uMui2rjg8Q4IkKTpFkuQFEUJQHgMR41CeTRTMDSw9NegzDF497vo+cwLOzKzvusmzfrBv7HGoAH4BcpDAY84GSAgkEfBKMG7PWKoPUCLZSR2ULdv54m4aiRlEWQOJ4gzhLlFRXXkpS9F0gVzEsl1HFcjy2turLvHyPxSHYsJMyib78p8YqAk+zBCNTiICkGsIymSqpvTqW4tr2o6umugZnrooR1A5WZwakJZEZRjGOWec55ZZjmeZNUm-Deb5FY6oF01JiFYWnpFPoxXFIQJWoLQpWl8a4DZ2VN93eV9yIJVlacm1Vd9j17WQDU1zNrUnTqHVsRSvVmANK-UCAq0Te9c9HfvFTzSuy3X+thRbdV4K1fth2ecdFTnX4JdG6aA7p8i-oYZ6ow3qYg+m4L6vtfpPyJo3Ro-AViAg+kQSwIBdDFzvp-aSuwsCWltJNAy5hSAIFqKYZGWA3IEMxBHAOrd2I+GwJMFOMlJrMNuvddssEiIAHJmCxFiHwHA29DhCMrMgyIqCOQYJ+nfYgOC8GHUIY8EhZDNEKEuNQ2hI4GH5jMswryWIKAZU4YMbhpj-Z8LHPYUglDMSCOoCImxkizQyKAA)
- [goals UI](https://www.bpmn-sketch-miner.ai/#EYBwNgdgXAbgjAKALRIQVQM4FMBOUEBKArhAAQAKOA9gOY4CGAtggPQukBqAllgO6kBBAMoBhAJJjS9HABdSIagCssAYzlhaVUgDJSVEDK5UIGBNz6kA5AHEq9MBkukAElUZZ59GlgRCsYVTkAeQMjEwQ4ADpOHn5GAE9SW3tTNkEZGRwuYCIZLAwoUlZ2JAA+JLswUggmLABuYtIy0iCydiCAMw7STPoVAGsGtObkqoATejyhkvKAEXp4jB6tHCw+gAtSGkrG5spaVYwl4GkzWKk1LhgPbZTGgQysnLyC3fLR6trppvKRN3AsHkxqQJlM3qQ-owAUC9G09F0egwBg0AKIADxA9AgwL6hmuWx25n4Kn+ARhtwcCHRmOxpBJULJWGBFNMABZouiuHJ9nQmAh0Ng8IQSBRqLzmGkiYJRBIpLJ5EpAqQNNsdHpQsZTFKbJVHC43B5Md5fP4lSFDJqEAAmaICMY40gAOQsowQH0dtTdlVIs3yKiyGogCHZpE53LFDGYAtw+GIZB5kcaUuE4kk0jkCioyjUys0av0FvC2tGetc7k8xr8ARz5rCpgAzNE0CBQR5ORhDBAaBV7MGOWiuaKDnzo0K40PxUnzinZemFVmlSqtLoC3WzhYdSknGXDV4fFWzYG2f3BwmmEA)
