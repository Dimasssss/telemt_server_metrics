# Server Metrics 2026-03-13 20:16:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 137873.4 (38h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4387470
telemt_connections_bad_total 37844
telemt_handshake_timeouts_total 105964
telemt_upstream_connect_attempt_total 28898
telemt_upstream_connect_success_total 28701
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 28898
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12736
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 6551
telemt_me_reconnect_attempts_total 29586
telemt_me_reconnect_success_total 19470
telemt_me_reader_eof_total 20896
telemt_me_idle_close_by_peer_total 20895
telemt_me_route_drop_no_conn_total 1651013
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4015393
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15913
telemt_desync_full_logged_total 4241
telemt_desync_suppressed_total 11672
telemt_desync_frames_bucket_total{bucket="1_2"} 3963
telemt_desync_frames_bucket_total{bucket="3_10"} 6063
telemt_desync_frames_bucket_total{bucket="gt_10"} 5887
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 20064
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 19457
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 594
telemt_user_connections_total{user="hello"} 4017554
telemt_user_connections_current{user="hello"} 1297
telemt_user_octets_from_client{user="hello"} 58606474676 (54.58 GB)
telemt_user_octets_to_client{user="hello"} 1267698541849 (1.15 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 368
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 37537.2 (10h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 536678
telemt_connections_bad_total 41360
telemt_handshake_timeouts_total 12085
telemt_upstream_connect_attempt_total 10818
telemt_upstream_connect_success_total 10602
telemt_upstream_connect_fail_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 10818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4182
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 216
telemt_me_keepalive_timeout_total 1877
telemt_me_reconnect_attempts_total 10106
telemt_me_reconnect_success_total 6687
telemt_me_reader_eof_total 7069
telemt_me_idle_close_by_peer_total 7068
telemt_me_route_drop_no_conn_total 199416
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 465221
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1562
telemt_desync_full_logged_total 420
telemt_desync_suppressed_total 1142
telemt_desync_frames_bucket_total{bucket="1_2"} 332
telemt_desync_frames_bucket_total{bucket="3_10"} 688
telemt_desync_frames_bucket_total{bucket="gt_10"} 542
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 6888
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 6679
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 467151
telemt_user_connections_current{user="hello"} 466
telemt_user_octets_from_client{user="hello"} 4992299941 (4.65 GB)
telemt_user_octets_to_client{user="hello"} 147982402296 (137.82 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 167494.0 (46h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3197980
telemt_connections_bad_total 29612
telemt_handshake_timeouts_total 213988
telemt_upstream_connect_attempt_total 37133
telemt_upstream_connect_success_total 37114
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 37133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17675
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 10193
telemt_me_reconnect_attempts_total 31020
telemt_me_reconnect_success_total 28450
telemt_me_reader_eof_total 30142
telemt_me_idle_close_by_peer_total 30141
telemt_me_route_drop_no_conn_total 1095503
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2649012
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8763
telemt_desync_full_logged_total 2910
telemt_desync_suppressed_total 5853
telemt_desync_frames_bucket_total{bucket="1_2"} 1443
telemt_desync_frames_bucket_total{bucket="3_10"} 3205
telemt_desync_frames_bucket_total{bucket="gt_10"} 4115
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 28793
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 28409
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 343
telemt_user_connections_total{user="hello"} 2648293
telemt_user_connections_current{user="hello"} 721
telemt_user_octets_from_client{user="hello"} 43655570688 (40.66 GB)
telemt_user_octets_to_client{user="hello"} 932041898417 (868.03 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 167494.5 (46h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2072241
telemt_connections_bad_total 22696
telemt_handshake_timeouts_total 195471
telemt_upstream_connect_attempt_total 52353
telemt_upstream_connect_success_total 49915
telemt_upstream_connect_fail_total 2301
telemt_upstream_connect_attempts_per_request{bucket="1"} 52079
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19714
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2300
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20203
telemt_me_reconnect_attempts_total 43546
telemt_me_reconnect_success_total 34538
telemt_me_reader_eof_total 37075
telemt_me_idle_close_by_peer_total 37068
telemt_me_route_drop_no_conn_total 732603
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1707870
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3684
telemt_desync_full_logged_total 1177
telemt_desync_suppressed_total 2507
telemt_desync_frames_bucket_total{bucket="1_2"} 971
telemt_desync_frames_bucket_total{bucket="3_10"} 1530
telemt_desync_frames_bucket_total{bucket="gt_10"} 1183
telemt_pool_swap_total 146
telemt_me_writer_removed_unexpected_total 35112
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 34514
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 574
telemt_user_connections_total{user="hello"} 1713739
telemt_user_connections_current{user="hello"} 503
telemt_user_octets_from_client{user="hello"} 26551783215 (24.73 GB)
telemt_user_octets_to_client{user="hello"} 643086134538 (598.92 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 36930.0 (10h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 574983
telemt_connections_bad_total 5734
telemt_handshake_timeouts_total 5501
telemt_upstream_connect_attempt_total 8155
telemt_upstream_connect_success_total 7889
telemt_upstream_connect_fail_total 266
telemt_upstream_connect_attempts_per_request{bucket="1"} 8155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4102
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 266
telemt_me_keepalive_timeout_total 968
telemt_me_reconnect_attempts_total 26982
telemt_me_reconnect_success_total 6042
telemt_me_reader_eof_total 6814
telemt_me_idle_close_by_peer_total 6813
telemt_me_route_drop_no_conn_total 218104
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 539334
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1478
telemt_desync_full_logged_total 457
telemt_desync_suppressed_total 1021
telemt_desync_frames_bucket_total{bucket="1_2"} 442
telemt_desync_frames_bucket_total{bucket="3_10"} 592
telemt_desync_frames_bucket_total{bucket="gt_10"} 444
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 6750
telemt_me_refill_failed_total 652
telemt_me_writer_restored_same_endpoint_total 6038
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 708
telemt_user_connections_total{user="hello"} 539281
telemt_user_connections_current{user="hello"} 561
telemt_user_octets_from_client{user="hello"} 6313077276 (5.88 GB)
telemt_user_octets_to_client{user="hello"} 171996967208 (160.18 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 66
```