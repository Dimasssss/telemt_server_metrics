# Server Metrics 2026-03-11 17:45:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 98282.9 (27h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2481953
telemt_connections_bad_total 46539
telemt_handshake_timeouts_total 55266
telemt_upstream_connect_attempt_total 20660
telemt_upstream_connect_success_total 20648
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 20660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10125
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5236
telemt_me_reconnect_attempts_total 33534
telemt_me_reconnect_success_total 15656
telemt_me_reader_eof_total 16956
telemt_me_idle_close_by_peer_total 16956
telemt_me_route_drop_no_conn_total 923655
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2270306
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11686
telemt_desync_full_logged_total 3210
telemt_desync_suppressed_total 8476
telemt_desync_frames_bucket_total{bucket="1_2"} 2888
telemt_desync_frames_bucket_total{bucket="3_10"} 4513
telemt_desync_frames_bucket_total{bucket="gt_10"} 4285
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 16390
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 15650
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 734
telemt_user_connections_total{user="hello"} 2268748
telemt_user_connections_current{user="hello"} 1296
telemt_user_octets_from_client{user="hello"} 30947365736 (28.82 GB)
telemt_user_octets_to_client{user="hello"} 641549365516 (597.49 GB)
telemt_user_unique_ips_current{user="hello"} 376
telemt_user_unique_ips_recent_window{user="hello"} 191
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 98339.2 (27h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 932993
telemt_connections_bad_total 16334
telemt_handshake_timeouts_total 81550
telemt_upstream_connect_attempt_total 30868
telemt_upstream_connect_success_total 27904
telemt_upstream_connect_fail_total 2964
telemt_upstream_connect_attempts_per_request{bucket="1"} 30868
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12521
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2040
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2964
telemt_me_keepalive_timeout_total 2759
telemt_me_reconnect_attempts_total 22101
telemt_me_reconnect_success_total 19993
telemt_me_reader_eof_total 21160
telemt_me_idle_close_by_peer_total 21157
telemt_me_route_drop_no_conn_total 353239
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 777980
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3064
telemt_desync_full_logged_total 978
telemt_desync_suppressed_total 2086
telemt_desync_frames_bucket_total{bucket="1_2"} 927
telemt_desync_frames_bucket_total{bucket="3_10"} 1100
telemt_desync_frames_bucket_total{bucket="gt_10"} 1037
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 20271
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 19970
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 780441
telemt_user_connections_current{user="hello"} 464
telemt_user_octets_from_client{user="hello"} 9382913970 (8.74 GB)
telemt_user_octets_to_client{user="hello"} 220613745080 (205.46 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 98339.2 (27h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1592294
telemt_connections_bad_total 9646
telemt_handshake_timeouts_total 128082
telemt_upstream_connect_attempt_total 25523
telemt_upstream_connect_success_total 25201
telemt_upstream_connect_fail_total 322
telemt_upstream_connect_attempts_per_request{bucket="1"} 25523
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13554
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11519
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 127
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 322
telemt_me_keepalive_timeout_total 1894
telemt_me_reconnect_attempts_total 45147
telemt_me_reconnect_success_total 19143
telemt_me_reader_eof_total 20800
telemt_me_idle_close_by_peer_total 20800
telemt_me_route_drop_no_conn_total 580413
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1393246
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3748
telemt_desync_full_logged_total 1091
telemt_desync_suppressed_total 2657
telemt_desync_frames_bucket_total{bucket="1_2"} 902
telemt_desync_frames_bucket_total{bucket="3_10"} 1426
telemt_desync_frames_bucket_total{bucket="gt_10"} 1420
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 20219
telemt_me_refill_failed_total 807
telemt_me_writer_restored_same_endpoint_total 19131
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1076
telemt_user_connections_total{user="hello"} 1392935
telemt_user_connections_current{user="hello"} 712
telemt_user_octets_from_client{user="hello"} 17194212645 (16.01 GB)
telemt_user_octets_to_client{user="hello"} 423621963577 (394.53 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 98339.8 (27h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1138941
telemt_connections_bad_total 77990
telemt_handshake_timeouts_total 107411
telemt_upstream_connect_attempt_total 26591
telemt_upstream_connect_success_total 26591
telemt_upstream_connect_attempts_per_request{bucket="1"} 26591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12074
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1260
telemt_me_reconnect_attempts_total 25014
telemt_me_reconnect_success_total 21658
telemt_me_reader_eof_total 22981
telemt_me_idle_close_by_peer_total 22980
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 376913
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 919830
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1929
telemt_desync_full_logged_total 739
telemt_desync_suppressed_total 1190
telemt_desync_frames_bucket_total{bucket="1_2"} 687
telemt_desync_frames_bucket_total{bucket="3_10"} 675
telemt_desync_frames_bucket_total{bucket="gt_10"} 567
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 21994
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 21625
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 336
telemt_user_connections_total{user="hello"} 919107
telemt_user_connections_current{user="hello"} 447
telemt_user_octets_from_client{user="hello"} 11046150056 (10.29 GB)
telemt_user_octets_to_client{user="hello"} 279798684852 (260.58 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 3015.7 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54735
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 292
telemt_upstream_connect_attempt_total 931
telemt_upstream_connect_success_total 931
telemt_upstream_connect_attempts_per_request{bucket="1"} 931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 385
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 729
telemt_me_reconnect_success_total 722
telemt_me_reader_eof_total 698
telemt_me_idle_close_by_peer_total 698
telemt_me_route_drop_no_conn_total 17627
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51517
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 112
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 76
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_me_writer_removed_unexpected_total 721
telemt_me_writer_restored_same_endpoint_total 700
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 256
telemt_user_connections_total{user="hello"} 51517
telemt_user_connections_current{user="hello"} 639
telemt_user_octets_from_client{user="hello"} 5811449684 (5.41 GB)
telemt_user_octets_to_client{user="hello"} 19053334068 (17.74 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 93
```