# Server Metrics 2026-03-13 17:07:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 126556.5 (35h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4027450
telemt_connections_bad_total 37515
telemt_handshake_timeouts_total 100264
telemt_upstream_connect_attempt_total 26923
telemt_upstream_connect_success_total 26746
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 26923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 117
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_keepalive_timeout_total 5604
telemt_me_reconnect_attempts_total 28191
telemt_me_reconnect_success_total 18086
telemt_me_reader_eof_total 19428
telemt_me_idle_close_by_peer_total 19427
telemt_me_route_drop_no_conn_total 1495024
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3677223
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14407
telemt_desync_full_logged_total 3810
telemt_desync_suppressed_total 10597
telemt_desync_frames_bucket_total{bucket="1_2"} 3592
telemt_desync_frames_bucket_total{bucket="3_10"} 5462
telemt_desync_frames_bucket_total{bucket="gt_10"} 5353
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 18652
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 18073
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 566
telemt_user_connections_total{user="hello"} 3679393
telemt_user_connections_current{user="hello"} 1697
telemt_user_octets_from_client{user="hello"} 51819247552 (48.26 GB)
telemt_user_octets_to_client{user="hello"} 1146848147017 (1.04 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 435
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 26220.3 (7h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 391673
telemt_connections_bad_total 28891
telemt_handshake_timeouts_total 10243
telemt_upstream_connect_attempt_total 7673
telemt_upstream_connect_success_total 7500
telemt_upstream_connect_fail_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 7673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3048
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 173
telemt_me_keepalive_timeout_total 1565
telemt_me_reconnect_attempts_total 8113
telemt_me_reconnect_success_total 4719
telemt_me_reader_eof_total 4999
telemt_me_idle_close_by_peer_total 4998
telemt_me_route_drop_no_conn_total 143809
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 341338
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1211
telemt_desync_full_logged_total 311
telemt_desync_suppressed_total 900
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 580
telemt_desync_frames_bucket_total{bucket="gt_10"} 395
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4881
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 4711
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 342675
telemt_user_connections_current{user="hello"} 627
telemt_user_octets_from_client{user="hello"} 3402373275 (3.17 GB)
telemt_user_octets_to_client{user="hello"} 100008001420 (93.14 GB)
telemt_user_msgs_from_client{user="hello"} 4402
telemt_user_msgs_to_client{user="hello"} 9145
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 156177.0 (43h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2947455
telemt_connections_bad_total 28321
telemt_handshake_timeouts_total 197531
telemt_upstream_connect_attempt_total 34878
telemt_upstream_connect_success_total 34868
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 34878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18032
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16704
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 127
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3382
telemt_me_reconnect_attempts_total 29316
telemt_me_reconnect_success_total 26762
telemt_me_reader_eof_total 28379
telemt_me_idle_close_by_peer_total 28378
telemt_me_route_drop_no_conn_total 1002907
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2431195
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8467
telemt_desync_full_logged_total 2801
telemt_desync_suppressed_total 5666
telemt_desync_frames_bucket_total{bucket="1_2"} 1361
telemt_desync_frames_bucket_total{bucket="3_10"} 3101
telemt_desync_frames_bucket_total{bucket="gt_10"} 4005
telemt_pool_swap_total 147
telemt_me_writer_removed_unexpected_total 27075
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 26721
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 313
telemt_user_connections_total{user="hello"} 2430557
telemt_user_connections_current{user="hello"} 1287
telemt_user_octets_from_client{user="hello"} 40093863536 (37.34 GB)
telemt_user_octets_to_client{user="hello"} 848691352317 (790.41 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 322
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 156177.3 (43h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1903497
telemt_connections_bad_total 18230
telemt_handshake_timeouts_total 176437
telemt_upstream_connect_attempt_total 48771
telemt_upstream_connect_success_total 46434
telemt_upstream_connect_fail_total 2200
telemt_upstream_connect_attempts_per_request{bucket="1"} 48497
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18531
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2199
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11946
telemt_me_reconnect_attempts_total 41785
telemt_me_reconnect_success_total 32803
telemt_me_reader_eof_total 35228
telemt_me_idle_close_by_peer_total 35221
telemt_me_route_drop_no_conn_total 675124
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1567245
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3111
telemt_desync_full_logged_total 1009
telemt_desync_suppressed_total 2102
telemt_desync_frames_bucket_total{bucket="1_2"} 859
telemt_desync_frames_bucket_total{bucket="3_10"} 1281
telemt_desync_frames_bucket_total{bucket="gt_10"} 971
telemt_pool_swap_total 135
telemt_me_writer_removed_unexpected_total 33346
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 32779
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 543
telemt_user_connections_total{user="hello"} 1571938
telemt_user_connections_current{user="hello"} 716
telemt_user_octets_from_client{user="hello"} 24290528165 (22.62 GB)
telemt_user_octets_to_client{user="hello"} 596442246918 (555.48 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 25612.6 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 419350
telemt_connections_bad_total 4414
telemt_handshake_timeouts_total 4220
telemt_upstream_connect_attempt_total 5838
telemt_upstream_connect_success_total 5648
telemt_upstream_connect_fail_total 190
telemt_upstream_connect_attempts_per_request{bucket="1"} 5838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3046
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 190
telemt_me_keepalive_timeout_total 845
telemt_me_reconnect_attempts_total 16045
telemt_me_reconnect_success_total 4335
telemt_me_reader_eof_total 4793
telemt_me_idle_close_by_peer_total 4793
telemt_me_route_drop_no_conn_total 162049
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 391751
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1255
telemt_desync_full_logged_total 398
telemt_desync_suppressed_total 857
telemt_desync_frames_bucket_total{bucket="1_2"} 411
telemt_desync_frames_bucket_total{bucket="3_10"} 500
telemt_desync_frames_bucket_total{bucket="gt_10"} 344
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4733
telemt_me_refill_failed_total 364
telemt_me_writer_restored_same_endpoint_total 4331
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 398
telemt_user_connections_total{user="hello"} 391727
telemt_user_connections_current{user="hello"} 929
telemt_user_octets_from_client{user="hello"} 4488088704 (4.18 GB)
telemt_user_octets_to_client{user="hello"} 123547424564 (115.06 GB)
telemt_user_unique_ips_current{user="hello"} 218
telemt_user_unique_ips_recent_window{user="hello"} 113
```