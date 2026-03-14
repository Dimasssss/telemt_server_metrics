# Server Metrics 2026-03-14 19:12:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 21291.7 (5h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 853170
telemt_connections_bad_total 40363
telemt_handshake_timeouts_total 12533
telemt_upstream_connect_attempt_total 4008
telemt_upstream_connect_success_total 3991
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 4008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2016
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 3680
telemt_me_reconnect_success_total 2877
telemt_me_reader_eof_total 3026
telemt_me_idle_close_by_peer_total 3026
telemt_me_route_drop_no_conn_total 326960
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 753777
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2597
telemt_desync_full_logged_total 742
telemt_desync_suppressed_total 1855
telemt_desync_frames_bucket_total{bucket="1_2"} 625
telemt_desync_frames_bucket_total{bucket="3_10"} 978
telemt_desync_frames_bucket_total{bucket="gt_10"} 994
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2951
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2868
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 753723
telemt_user_connections_current{user="hello"} 1686
telemt_user_octets_from_client{user="hello"} 13413177524 (12.49 GB)
telemt_user_octets_to_client{user="hello"} 250461737076 (233.26 GB)
telemt_user_unique_ips_current{user="hello"} 474
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 21297.0 (5h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 329459
telemt_connections_bad_total 23095
telemt_handshake_timeouts_total 10070
telemt_upstream_connect_attempt_total 4431
telemt_upstream_connect_success_total 4378
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 4431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2319
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1973
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 385
telemt_me_reconnect_attempts_total 4059
telemt_me_reconnect_success_total 3266
telemt_me_reader_eof_total 3423
telemt_me_idle_close_by_peer_total 3423
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 102629
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 276988
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1166
telemt_desync_full_logged_total 362
telemt_desync_suppressed_total 804
telemt_desync_frames_bucket_total{bucket="1_2"} 456
telemt_desync_frames_bucket_total{bucket="3_10"} 429
telemt_desync_frames_bucket_total{bucket="gt_10"} 281
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3358
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 3250
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 276919
telemt_user_connections_current{user="hello"} 575
telemt_user_octets_from_client{user="hello"} 3774041740 (3.51 GB)
telemt_user_octets_to_client{user="hello"} 97451215820 (90.76 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 21160.1 (5h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 689900
telemt_connections_bad_total 2795
telemt_handshake_timeouts_total 136019
telemt_upstream_connect_attempt_total 4160
telemt_upstream_connect_success_total 4146
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 4160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2021
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 6954
telemt_me_reconnect_success_total 3046
telemt_me_reader_eof_total 3273
telemt_me_idle_close_by_peer_total 3273
telemt_me_route_drop_no_conn_total 167458
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 470754
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1674
telemt_desync_full_logged_total 646
telemt_desync_suppressed_total 1028
telemt_desync_frames_bucket_total{bucket="1_2"} 227
telemt_desync_frames_bucket_total{bucket="3_10"} 585
telemt_desync_frames_bucket_total{bucket="gt_10"} 862
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3197
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3013
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 470602
telemt_user_connections_current{user="hello"} 1060
telemt_user_octets_from_client{user="hello"} 6825282972 (6.36 GB)
telemt_user_octets_to_client{user="hello"} 167769905960 (156.25 GB)
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 21014.4 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 381436
telemt_connections_bad_total 87409
telemt_handshake_timeouts_total 45385
telemt_upstream_connect_attempt_total 5003
telemt_upstream_connect_success_total 5002
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2383
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 180
telemt_me_reconnect_attempts_total 4827
telemt_me_reconnect_success_total 3910
telemt_me_reader_eof_total 4089
telemt_me_idle_close_by_peer_total 4089
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 85957
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 242487
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 10
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 532
telemt_desync_full_logged_total 182
telemt_desync_suppressed_total 350
telemt_desync_frames_bucket_total{bucket="1_2"} 198
telemt_desync_frames_bucket_total{bucket="3_10"} 162
telemt_desync_frames_bucket_total{bucket="gt_10"} 172
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3983
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3900
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 242418
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 3560450296 (3.32 GB)
telemt_user_octets_to_client{user="hello"} 77921388696 (72.57 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 21309.9 (5h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 324565
telemt_connections_bad_total 1243
telemt_handshake_timeouts_total 3548
telemt_upstream_connect_attempt_total 4404
telemt_upstream_connect_success_total 4314
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 4404
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_timeout_total 117
telemt_me_reconnect_attempts_total 3891
telemt_me_reconnect_success_total 3221
telemt_me_reader_eof_total 3391
telemt_me_idle_close_by_peer_total 3391
telemt_me_route_drop_no_conn_total 101172
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 300892
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 769
telemt_desync_full_logged_total 284
telemt_desync_suppressed_total 485
telemt_desync_frames_bucket_total{bucket="1_2"} 268
telemt_desync_frames_bucket_total{bucket="3_10"} 234
telemt_desync_frames_bucket_total{bucket="gt_10"} 267
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3304
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 3203
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 300880
telemt_user_connections_current{user="hello"} 698
telemt_user_octets_from_client{user="hello"} 4650794656 (4.33 GB)
telemt_user_octets_to_client{user="hello"} 127440391144 (118.69 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 80
```