# Server Metrics 2026-03-10 20:37:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 22201.3 (6h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 651258
telemt_connections_bad_total 8009
telemt_handshake_timeouts_total 7765
telemt_upstream_connect_attempt_total 4687
telemt_upstream_connect_success_total 4678
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 4687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2327
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 15142
telemt_me_reconnect_success_total 3490
telemt_me_reader_eof_total 3899
telemt_me_idle_close_by_peer_total 3899
telemt_me_route_drop_no_conn_total 272642
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 614201
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3165
telemt_desync_full_logged_total 859
telemt_desync_suppressed_total 2306
telemt_desync_frames_bucket_total{bucket="1_2"} 890
telemt_desync_frames_bucket_total{bucket="3_10"} 1192
telemt_desync_frames_bucket_total{bucket="gt_10"} 1083
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3875
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 3484
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 385
telemt_user_connections_total{user="hello"} 614009
telemt_user_connections_current{user="hello"} 986
telemt_user_octets_from_client{user="hello"} 8787000288 (8.18 GB)
telemt_user_octets_to_client{user="hello"} 184276583372 (171.62 GB)
telemt_user_unique_ips_current{user="hello"} 280
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 22257.9 (6h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 287847
telemt_connections_bad_total 1828
telemt_handshake_timeouts_total 17068
telemt_upstream_connect_attempt_total 11064
telemt_upstream_connect_success_total 8207
telemt_upstream_connect_fail_total 2857
telemt_upstream_connect_attempts_per_request{bucket="1"} 11064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2580
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2028
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2857
telemt_me_keepalive_timeout_total 1233
telemt_me_reconnect_attempts_total 4906
telemt_me_reconnect_success_total 4105
telemt_me_reader_eof_total 4294
telemt_me_idle_close_by_peer_total 4292
telemt_me_route_drop_no_conn_total 156702
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 240743
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1351
telemt_desync_full_logged_total 363
telemt_desync_suppressed_total 988
telemt_desync_frames_bucket_total{bucket="1_2"} 433
telemt_desync_frames_bucket_total{bucket="3_10"} 483
telemt_desync_frames_bucket_total{bucket="gt_10"} 435
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 4183
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 4084
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 243006
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 2445097186 (2.28 GB)
telemt_user_octets_to_client{user="hello"} 57303088120 (53.37 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 22257.9 (6h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 464202
telemt_connections_bad_total 2424
telemt_handshake_timeouts_total 32534
telemt_upstream_connect_attempt_total 6609
telemt_upstream_connect_success_total 6511
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 6609
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2595
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 160
telemt_me_reconnect_attempts_total 12641
telemt_me_reconnect_success_total 4290
telemt_me_reader_eof_total 4673
telemt_me_idle_close_by_peer_total 4673
telemt_me_route_drop_no_conn_total 160628
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 403435
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1341
telemt_desync_full_logged_total 373
telemt_desync_suppressed_total 968
telemt_desync_frames_bucket_total{bucket="1_2"} 308
telemt_desync_frames_bucket_total{bucket="3_10"} 457
telemt_desync_frames_bucket_total{bucket="gt_10"} 576
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4625
telemt_me_refill_failed_total 259
telemt_me_writer_restored_same_endpoint_total 4279
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 335
telemt_user_connections_total{user="hello"} 404379
telemt_user_connections_current{user="hello"} 516
telemt_user_octets_from_client{user="hello"} 5864497641 (5.46 GB)
telemt_user_octets_to_client{user="hello"} 127249821589 (118.51 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 22258.3 (6h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 314776
telemt_connections_bad_total 21808
telemt_handshake_timeouts_total 27096
telemt_upstream_connect_attempt_total 6068
telemt_upstream_connect_success_total 6068
telemt_upstream_connect_attempts_per_request{bucket="1"} 6068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2821
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 5934
telemt_me_reconnect_success_total 4916
telemt_me_reader_eof_total 5153
telemt_me_idle_close_by_peer_total 5153
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 102071
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 253858
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 665
telemt_desync_full_logged_total 271
telemt_desync_suppressed_total 394
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 237
telemt_desync_frames_bucket_total{bucket="gt_10"} 171
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 4996
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 4903
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 253556
telemt_user_connections_current{user="hello"} 319
telemt_user_octets_from_client{user="hello"} 3829872556 (3.57 GB)
telemt_user_octets_to_client{user="hello"} 79462817080 (74.01 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 22258.1 (6h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331711
telemt_connections_bad_total 1039
telemt_handshake_timeouts_total 2089
telemt_upstream_connect_attempt_total 7021
telemt_upstream_connect_success_total 6994
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 7021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3254
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 149
telemt_me_reconnect_attempts_total 9567
telemt_me_reconnect_success_total 5816
telemt_me_reader_eof_total 6080
telemt_me_idle_close_by_peer_total 6080
telemt_me_route_drop_no_conn_total 120249
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 311990
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1801
telemt_desync_full_logged_total 676
telemt_desync_suppressed_total 1125
telemt_desync_frames_bucket_total{bucket="1_2"} 696
telemt_desync_frames_bucket_total{bucket="3_10"} 758
telemt_desync_frames_bucket_total{bucket="gt_10"} 347
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 6018
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 5816
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 311891
telemt_user_connections_current{user="hello"} 517
telemt_user_octets_from_client{user="hello"} 5995828568 (5.58 GB)
telemt_user_octets_to_client{user="hello"} 103874529284 (96.74 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 74
```