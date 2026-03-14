# Server Metrics 2026-03-14 21:05:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 28046.5 (7h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1046117
telemt_connections_bad_total 42348
telemt_handshake_timeouts_total 14713
telemt_upstream_connect_attempt_total 5117
telemt_upstream_connect_success_total 5094
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2521
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 4439
telemt_me_reconnect_success_total 3631
telemt_me_reader_eof_total 3831
telemt_me_idle_close_by_peer_total 3831
telemt_me_route_drop_no_conn_total 399957
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 931093
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3137
telemt_desync_full_logged_total 901
telemt_desync_suppressed_total 2236
telemt_desync_frames_bucket_total{bucket="1_2"} 738
telemt_desync_frames_bucket_total{bucket="3_10"} 1163
telemt_desync_frames_bucket_total{bucket="gt_10"} 1236
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3714
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 3622
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 931035
telemt_user_connections_current{user="hello"} 1377
telemt_user_octets_from_client{user="hello"} 16558763836 (15.42 GB)
telemt_user_octets_to_client{user="hello"} 313613696992 (292.08 GB)
telemt_user_unique_ips_current{user="hello"} 416
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 28051.8 (7h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 411743
telemt_connections_bad_total 31193
telemt_handshake_timeouts_total 12872
telemt_upstream_connect_attempt_total 6039
telemt_upstream_connect_success_total 5979
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 6039
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2762
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 479
telemt_me_reconnect_attempts_total 5315
telemt_me_reconnect_success_total 4518
telemt_me_reader_eof_total 4726
telemt_me_idle_close_by_peer_total 4726
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 120949
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 344182
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1683
telemt_desync_full_logged_total 445
telemt_desync_suppressed_total 1238
telemt_desync_frames_bucket_total{bucket="1_2"} 698
telemt_desync_frames_bucket_total{bucket="3_10"} 584
telemt_desync_frames_bucket_total{bucket="gt_10"} 401
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4635
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 4495
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 344126
telemt_user_connections_current{user="hello"} 484
telemt_user_octets_from_client{user="hello"} 5491974116 (5.11 GB)
telemt_user_octets_to_client{user="hello"} 119491439236 (111.29 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 27914.6 (7h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 895358
telemt_connections_bad_total 3651
telemt_handshake_timeouts_total 223399
telemt_upstream_connect_attempt_total 5390
telemt_upstream_connect_success_total 5373
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 5390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2592
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 7880
telemt_me_reconnect_success_total 3967
telemt_me_reader_eof_total 4251
telemt_me_idle_close_by_peer_total 4251
telemt_me_route_drop_no_conn_total 200224
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 571137
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2147
telemt_desync_full_logged_total 822
telemt_desync_suppressed_total 1325
telemt_desync_frames_bucket_total{bucket="1_2"} 316
telemt_desync_frames_bucket_total{bucket="3_10"} 752
telemt_desync_frames_bucket_total{bucket="gt_10"} 1079
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4134
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3934
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 570964
telemt_user_connections_current{user="hello"} 742
telemt_user_octets_from_client{user="hello"} 8805178328 (8.20 GB)
telemt_user_octets_to_client{user="hello"} 214278359024 (199.56 GB)
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 27769.2 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 475305
telemt_connections_bad_total 100171
telemt_handshake_timeouts_total 54806
telemt_upstream_connect_attempt_total 6378
telemt_upstream_connect_success_total 6377
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6378
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3090
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 214
telemt_me_reconnect_attempts_total 5901
telemt_me_reconnect_success_total 4978
telemt_me_reader_eof_total 5219
telemt_me_idle_close_by_peer_total 5219
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 109584
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 312289
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 702
telemt_desync_full_logged_total 244
telemt_desync_suppressed_total 458
telemt_desync_frames_bucket_total{bucket="1_2"} 242
telemt_desync_frames_bucket_total{bucket="3_10"} 231
telemt_desync_frames_bucket_total{bucket="gt_10"} 229
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5065
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4966
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 312203
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 4353683892 (4.05 GB)
telemt_user_octets_to_client{user="hello"} 95581732368 (89.02 GB)
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 28064.7 (7h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 398635
telemt_connections_bad_total 1391
telemt_handshake_timeouts_total 3965
telemt_upstream_connect_attempt_total 5972
telemt_upstream_connect_success_total 5853
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 5972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2957
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 5087
telemt_me_reconnect_success_total 4411
telemt_me_reader_eof_total 4654
telemt_me_idle_close_by_peer_total 4654
telemt_me_route_drop_no_conn_total 125593
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 370096
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 999
telemt_desync_full_logged_total 348
telemt_desync_suppressed_total 651
telemt_desync_frames_bucket_total{bucket="1_2"} 329
telemt_desync_frames_bucket_total{bucket="3_10"} 312
telemt_desync_frames_bucket_total{bucket="gt_10"} 358
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4512
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 4393
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 370060
telemt_user_connections_current{user="hello"} 532
telemt_user_octets_from_client{user="hello"} 5926374600 (5.52 GB)
telemt_user_octets_to_client{user="hello"} 154115744432 (143.53 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 66
```