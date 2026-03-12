# Server Metrics 2026-03-12 11:46:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 20870.6 (5h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 708101
telemt_connections_bad_total 1498
telemt_handshake_timeouts_total 4026
telemt_upstream_connect_attempt_total 4056
telemt_upstream_connect_success_total 4028
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 4056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1819
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 317
telemt_me_reconnect_attempts_total 6824
telemt_me_reconnect_success_total 2931
telemt_me_reader_eof_total 3153
telemt_me_idle_close_by_peer_total 3153
telemt_me_route_drop_no_conn_total 248698
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 683026
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3392
telemt_desync_full_logged_total 859
telemt_desync_suppressed_total 2533
telemt_desync_frames_bucket_total{bucket="1_2"} 868
telemt_desync_frames_bucket_total{bucket="3_10"} 1241
telemt_desync_frames_bucket_total{bucket="gt_10"} 1283
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3082
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2918
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 682878
telemt_user_connections_current{user="hello"} 1538
telemt_user_octets_from_client{user="hello"} 11843944512 (11.03 GB)
telemt_user_octets_to_client{user="hello"} 190453366900 (177.37 GB)
telemt_user_unique_ips_current{user="hello"} 430
telemt_user_unique_ips_recent_window{user="hello"} 229
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 50491.0 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 368669
telemt_connections_bad_total 4413
telemt_handshake_timeouts_total 16656
telemt_upstream_connect_attempt_total 12405
telemt_upstream_connect_success_total 12399
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 12405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6283
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 822
telemt_me_reconnect_attempts_total 9730
telemt_me_reconnect_success_total 9675
telemt_me_reader_eof_total 10286
telemt_me_idle_close_by_peer_total 10286
telemt_me_route_drop_no_conn_total 105098
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 326504
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 916
telemt_desync_full_logged_total 317
telemt_desync_suppressed_total 599
telemt_desync_frames_bucket_total{bucket="1_2"} 335
telemt_desync_frames_bucket_total{bucket="3_10"} 323
telemt_desync_frames_bucket_total{bucket="gt_10"} 258
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 9763
telemt_me_writer_restored_same_endpoint_total 9666
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 326971
telemt_user_connections_current{user="hello"} 549
telemt_user_octets_from_client{user="hello"} 4498706715 (4.19 GB)
telemt_user_octets_to_client{user="hello"} 114212819906 (106.37 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 50490.8 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 854092
telemt_connections_bad_total 4194
telemt_handshake_timeouts_total 63597
telemt_upstream_connect_attempt_total 12381
telemt_upstream_connect_success_total 12376
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 12381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5524
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 704
telemt_me_reconnect_attempts_total 9571
telemt_me_reconnect_success_total 9491
telemt_me_reader_eof_total 9984
telemt_me_idle_close_by_peer_total 9984
telemt_me_route_drop_no_conn_total 203938
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 571051
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2596
telemt_desync_full_logged_total 767
telemt_desync_suppressed_total 1829
telemt_desync_frames_bucket_total{bucket="1_2"} 341
telemt_desync_frames_bucket_total{bucket="3_10"} 901
telemt_desync_frames_bucket_total{bucket="gt_10"} 1354
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 9513
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 9450
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 571290
telemt_user_connections_current{user="hello"} 836
telemt_user_octets_from_client{user="hello"} 7627238548 (7.10 GB)
telemt_user_octets_to_client{user="hello"} 182583531409 (170.04 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 256
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 50491.3 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 467757
telemt_connections_bad_total 5700
telemt_handshake_timeouts_total 43463
telemt_upstream_connect_attempt_total 13413
telemt_upstream_connect_success_total 13358
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 13412
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5750
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 1003
telemt_me_reconnect_attempts_total 10870
telemt_me_reconnect_success_total 10823
telemt_me_reader_eof_total 11478
telemt_me_idle_close_by_peer_total 11478
telemt_me_route_drop_no_conn_total 153190
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 388859
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 776
telemt_desync_full_logged_total 272
telemt_desync_suppressed_total 504
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 325
telemt_desync_frames_bucket_total{bucket="gt_10"} 215
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 10902
telemt_me_writer_restored_same_endpoint_total 10802
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 388682
telemt_user_connections_current{user="hello"} 609
telemt_user_octets_from_client{user="hello"} 4469183632 (4.16 GB)
telemt_user_octets_to_client{user="hello"} 147241104204 (137.13 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 50491.1 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 526420
telemt_connections_bad_total 1680
telemt_handshake_timeouts_total 4035
telemt_upstream_connect_attempt_total 16495
telemt_upstream_connect_success_total 16304
telemt_upstream_connect_fail_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 16495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7824
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 191
telemt_me_keepalive_timeout_total 787
telemt_me_reconnect_attempts_total 15782
telemt_me_reconnect_success_total 13777
telemt_me_reader_eof_total 14313
telemt_me_idle_close_by_peer_total 14313
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 173454
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 492909
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2089
telemt_desync_full_logged_total 698
telemt_desync_suppressed_total 1391
telemt_desync_frames_bucket_total{bucket="1_2"} 618
telemt_desync_frames_bucket_total{bucket="3_10"} 724
telemt_desync_frames_bucket_total{bucket="gt_10"} 747
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 13973
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 13751
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 196
telemt_user_connections_total{user="hello"} 492832
telemt_user_connections_current{user="hello"} 795
telemt_user_octets_from_client{user="hello"} 5802858852 (5.40 GB)
telemt_user_octets_to_client{user="hello"} 120339773844 (112.08 GB)
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 114
```