# Server Metrics 2026-03-15 15:47:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 63155.0 (17h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2062721
telemt_connections_bad_total 111748
telemt_handshake_timeouts_total 24493
telemt_upstream_connect_attempt_total 12641
telemt_upstream_connect_success_total 12585
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 12641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5985
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 14290
telemt_me_reconnect_success_total 9395
telemt_me_reader_eof_total 10041
telemt_me_idle_close_by_peer_total 10041
telemt_me_route_drop_no_conn_total 710355
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1743282
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6663
telemt_desync_full_logged_total 1840
telemt_desync_suppressed_total 4823
telemt_desync_frames_bucket_total{bucket="1_2"} 1648
telemt_desync_frames_bucket_total{bucket="3_10"} 2560
telemt_desync_frames_bucket_total{bucket="gt_10"} 2455
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 9701
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9384
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 306
telemt_user_connections_total{user="hello"} 1742792
telemt_user_connections_current{user="hello"} 2267
telemt_user_octets_from_client{user="hello"} 25637338940 (23.88 GB)
telemt_user_octets_to_client{user="hello"} 670252357616 (624.22 GB)
telemt_user_unique_ips_current{user="hello"} 679
telemt_user_unique_ips_recent_window{user="hello"} 277
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 63155.7 (17h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 821005
telemt_connections_bad_total 43765
telemt_handshake_timeouts_total 59490
telemt_upstream_connect_attempt_total 15900
telemt_upstream_connect_success_total 15824
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 15900
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7240
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 12393
telemt_me_reconnect_success_total 12295
telemt_me_reader_eof_total 12993
telemt_me_idle_close_by_peer_total 12993
telemt_me_route_drop_no_conn_total 207176
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 625063
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2078
telemt_desync_full_logged_total 699
telemt_desync_suppressed_total 1379
telemt_desync_frames_bucket_total{bucket="1_2"} 765
telemt_desync_frames_bucket_total{bucket="3_10"} 763
telemt_desync_frames_bucket_total{bucket="gt_10"} 550
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 12453
telemt_me_writer_restored_same_endpoint_total 12283
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 625305
telemt_user_connections_current{user="hello"} 623
telemt_user_octets_from_client{user="hello"} 8718066243 (8.12 GB)
telemt_user_octets_to_client{user="hello"} 234982290424 (218.84 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 63155.8 (17h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1841183
telemt_connections_bad_total 47885
telemt_handshake_timeouts_total 182972
telemt_upstream_connect_attempt_total 13791
telemt_upstream_connect_success_total 13726
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 13791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6586
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 11775
telemt_me_reconnect_success_total 10512
telemt_me_reader_eof_total 11141
telemt_me_idle_close_by_peer_total 11141
telemt_me_route_drop_no_conn_total 479706
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1108578
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2700
telemt_desync_full_logged_total 993
telemt_desync_suppressed_total 1707
telemt_desync_frames_bucket_total{bucket="1_2"} 625
telemt_desync_frames_bucket_total{bucket="3_10"} 1051
telemt_desync_frames_bucket_total{bucket="gt_10"} 1024
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 10699
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 10493
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 1104544
telemt_user_connections_current{user="hello"} 1361
telemt_user_octets_from_client{user="hello"} 15931700772 (14.84 GB)
telemt_user_octets_to_client{user="hello"} 393286907992 (366.28 GB)
telemt_user_unique_ips_current{user="hello"} 405
telemt_user_unique_ips_recent_window{user="hello"} 195
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 63155.7 (17h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 868732
telemt_connections_bad_total 76666
telemt_handshake_timeouts_total 42662
telemt_upstream_connect_attempt_total 168185
telemt_upstream_connect_success_total 167669
telemt_upstream_connect_fail_total 516
telemt_upstream_connect_attempts_per_request{bucket="1"} 168185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12556
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 516
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 52856
telemt_me_reconnect_success_total 12411
telemt_me_reader_eof_total 14027
telemt_me_idle_close_by_peer_total 14027
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 193254
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 514887
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1414
telemt_desync_full_logged_total 368
telemt_desync_suppressed_total 1046
telemt_desync_frames_bucket_total{bucket="1_2"} 371
telemt_desync_frames_bucket_total{bucket="3_10"} 569
telemt_desync_frames_bucket_total{bucket="gt_10"} 474
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 13801
telemt_me_refill_failed_total 1265
telemt_me_writer_restored_same_endpoint_total 12376
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1390
telemt_user_connections_total{user="hello"} 666538
telemt_user_connections_current{user="hello"} 805
telemt_user_octets_from_client{user="hello"} 13112763634 (12.21 GB)
telemt_user_octets_to_client{user="hello"} 235806538013 (219.61 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 63156.6 (17h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 876098
telemt_connections_bad_total 9435
telemt_handshake_timeouts_total 19242
telemt_upstream_connect_attempt_total 14050
telemt_upstream_connect_success_total 13971
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 14050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6459
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7501
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 14464
telemt_me_reconnect_success_total 10781
telemt_me_reader_eof_total 11506
telemt_me_idle_close_by_peer_total 11506
telemt_me_route_drop_no_conn_total 218379
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 721325
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2493
telemt_desync_full_logged_total 849
telemt_desync_suppressed_total 1644
telemt_desync_frames_bucket_total{bucket="1_2"} 758
telemt_desync_frames_bucket_total{bucket="3_10"} 959
telemt_desync_frames_bucket_total{bucket="gt_10"} 776
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 11023
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 10773
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 242
telemt_user_connections_total{user="hello"} 721365
telemt_user_connections_current{user="hello"} 870
telemt_user_octets_from_client{user="hello"} 8847243092 (8.24 GB)
telemt_user_octets_to_client{user="hello"} 258876020884 (241.10 GB)
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 115
```