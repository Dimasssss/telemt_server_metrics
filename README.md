# Server Metrics 2026-03-11 19:32:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 104712.8 (29h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2660120
telemt_connections_bad_total 48658
telemt_handshake_timeouts_total 58569
telemt_upstream_connect_attempt_total 22078
telemt_upstream_connect_success_total 22066
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 22078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10797
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5344
telemt_me_reconnect_attempts_total 34642
telemt_me_reconnect_success_total 16749
telemt_me_reader_eof_total 18107
telemt_me_idle_close_by_peer_total 18107
telemt_me_route_drop_no_conn_total 1004813
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2431140
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12319
telemt_desync_full_logged_total 3415
telemt_desync_suppressed_total 8904
telemt_desync_frames_bucket_total{bucket="1_2"} 3015
telemt_desync_frames_bucket_total{bucket="3_10"} 4762
telemt_desync_frames_bucket_total{bucket="gt_10"} 4542
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 17500
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 16743
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 751
telemt_user_connections_total{user="hello"} 2429491
telemt_user_connections_current{user="hello"} 1126
telemt_user_octets_from_client{user="hello"} 36343048124 (33.85 GB)
telemt_user_octets_to_client{user="hello"} 688960613216 (641.64 GB)
telemt_user_unique_ips_current{user="hello"} 333
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 104769.4 (29h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 989531
telemt_connections_bad_total 16474
telemt_handshake_timeouts_total 89240
telemt_upstream_connect_attempt_total 32302
telemt_upstream_connect_success_total 29331
telemt_upstream_connect_fail_total 2971
telemt_upstream_connect_attempts_per_request{bucket="1"} 32302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13210
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2060
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2971
telemt_me_keepalive_timeout_total 2854
telemt_me_reconnect_attempts_total 23220
telemt_me_reconnect_success_total 21102
telemt_me_reader_eof_total 22351
telemt_me_idle_close_by_peer_total 22348
telemt_me_route_drop_no_conn_total 374144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 825417
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3267
telemt_desync_full_logged_total 1063
telemt_desync_suppressed_total 2204
telemt_desync_frames_bucket_total{bucket="1_2"} 1038
telemt_desync_frames_bucket_total{bucket="3_10"} 1162
telemt_desync_frames_bucket_total{bucket="gt_10"} 1067
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 21406
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 21079
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 304
telemt_user_connections_total{user="hello"} 827863
telemt_user_connections_current{user="hello"} 412
telemt_user_octets_from_client{user="hello"} 9945715178 (9.26 GB)
telemt_user_octets_to_client{user="hello"} 239817573284 (223.35 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 104769.3 (29h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1705944
telemt_connections_bad_total 10609
telemt_handshake_timeouts_total 134207
telemt_upstream_connect_attempt_total 27003
telemt_upstream_connect_success_total 26664
telemt_upstream_connect_fail_total 339
telemt_upstream_connect_attempts_per_request{bucket="1"} 27003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12107
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 339
telemt_me_keepalive_timeout_total 1988
telemt_me_reconnect_attempts_total 52657
telemt_me_reconnect_success_total 20282
telemt_me_reader_eof_total 22152
telemt_me_idle_close_by_peer_total 22152
telemt_me_route_drop_no_conn_total 621470
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1496690
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4113
telemt_desync_full_logged_total 1212
telemt_desync_suppressed_total 2901
telemt_desync_frames_bucket_total{bucket="1_2"} 961
telemt_desync_frames_bucket_total{bucket="3_10"} 1560
telemt_desync_frames_bucket_total{bucket="gt_10"} 1592
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 21573
telemt_me_refill_failed_total 1006
telemt_me_writer_restored_same_endpoint_total 20270
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1291
telemt_user_connections_total{user="hello"} 1496343
telemt_user_connections_current{user="hello"} 709
telemt_user_octets_from_client{user="hello"} 19298207817 (17.97 GB)
telemt_user_octets_to_client{user="hello"} 456261172153 (424.93 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 104769.8 (29h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1218872
telemt_connections_bad_total 78201
telemt_handshake_timeouts_total 110776
telemt_upstream_connect_attempt_total 28327
telemt_upstream_connect_success_total 28327
telemt_upstream_connect_attempts_per_request{bucket="1"} 28327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15446
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12875
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1440
telemt_me_reconnect_attempts_total 27690
telemt_me_reconnect_success_total 23074
telemt_me_reader_eof_total 24499
telemt_me_idle_close_by_peer_total 24498
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 407358
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 994757
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2139
telemt_desync_full_logged_total 804
telemt_desync_suppressed_total 1335
telemt_desync_frames_bucket_total{bucket="1_2"} 765
telemt_desync_frames_bucket_total{bucket="3_10"} 725
telemt_desync_frames_bucket_total{bucket="gt_10"} 649
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 23460
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23041
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 386
telemt_user_connections_total{user="hello"} 993969
telemt_user_connections_current{user="hello"} 456
telemt_user_octets_from_client{user="hello"} 11820810180 (11.01 GB)
telemt_user_octets_to_client{user="hello"} 302352984968 (281.59 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 9445.8 (2h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149251
telemt_connections_bad_total 1266
telemt_handshake_timeouts_total 1155
telemt_upstream_connect_attempt_total 2827
telemt_upstream_connect_success_total 2826
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1343
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2315
telemt_me_reconnect_success_total 2294
telemt_me_reader_eof_total 2357
telemt_me_idle_close_by_peer_total 2357
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 51253
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 135816
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 281
telemt_desync_full_logged_total 88
telemt_desync_suppressed_total 193
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 121
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2321
telemt_me_writer_restored_same_endpoint_total 2269
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 135782
telemt_user_connections_current{user="hello"} 657
telemt_user_octets_from_client{user="hello"} 7460502516 (6.95 GB)
telemt_user_octets_to_client{user="hello"} 46394585752 (43.21 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 76
```