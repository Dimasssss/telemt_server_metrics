# Server Metrics 2026-03-15 16:27:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 65607.1 (18h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2205766
telemt_connections_bad_total 130041
telemt_handshake_timeouts_total 27086
telemt_upstream_connect_attempt_total 12957
telemt_upstream_connect_success_total 12901
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 12957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6143
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 14518
telemt_me_reconnect_success_total 9623
telemt_me_reader_eof_total 10285
telemt_me_idle_close_by_peer_total 10285
telemt_me_route_drop_no_conn_total 760153
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1855396
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7205
telemt_desync_full_logged_total 1983
telemt_desync_suppressed_total 5222
telemt_desync_frames_bucket_total{bucket="1_2"} 1751
telemt_desync_frames_bucket_total{bucket="3_10"} 2765
telemt_desync_frames_bucket_total{bucket="gt_10"} 2689
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 9935
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9612
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 312
telemt_user_connections_total{user="hello"} 1854893
telemt_user_connections_current{user="hello"} 2364
telemt_user_octets_from_client{user="hello"} 27195790844 (25.33 GB)
telemt_user_octets_to_client{user="hello"} 708754044184 (660.08 GB)
telemt_user_unique_ips_current{user="hello"} 663
telemt_user_unique_ips_recent_window{user="hello"} 286
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 65607.9 (18h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 865228
telemt_connections_bad_total 46758
telemt_handshake_timeouts_total 60541
telemt_upstream_connect_attempt_total 16553
telemt_upstream_connect_success_total 16473
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 16553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7535
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 38
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 12952
telemt_me_reconnect_success_total 12848
telemt_me_reader_eof_total 13557
telemt_me_idle_close_by_peer_total 13557
telemt_me_route_drop_no_conn_total 220960
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 662337
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2106
telemt_desync_full_logged_total 711
telemt_desync_suppressed_total 1395
telemt_desync_frames_bucket_total{bucket="1_2"} 769
telemt_desync_frames_bucket_total{bucket="3_10"} 778
telemt_desync_frames_bucket_total{bucket="gt_10"} 559
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 13014
telemt_me_writer_restored_same_endpoint_total 12836
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 662580
telemt_user_connections_current{user="hello"} 800
telemt_user_octets_from_client{user="hello"} 9190249399 (8.56 GB)
telemt_user_octets_to_client{user="hello"} 251620228952 (234.34 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 249
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 65607.8 (18h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1958772
telemt_connections_bad_total 48301
telemt_handshake_timeouts_total 193564
telemt_upstream_connect_attempt_total 14240
telemt_upstream_connect_success_total 14172
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 14240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6786
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 12133
telemt_me_reconnect_success_total 10865
telemt_me_reader_eof_total 11506
telemt_me_idle_close_by_peer_total 11506
telemt_me_route_drop_no_conn_total 504781
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1179938
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2936
telemt_desync_full_logged_total 1066
telemt_desync_suppressed_total 1870
telemt_desync_frames_bucket_total{bucket="1_2"} 681
telemt_desync_frames_bucket_total{bucket="3_10"} 1131
telemt_desync_frames_bucket_total{bucket="gt_10"} 1124
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 11056
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 10846
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 1175899
telemt_user_connections_current{user="hello"} 1292
telemt_user_octets_from_client{user="hello"} 17078178476 (15.91 GB)
telemt_user_octets_to_client{user="hello"} 424430091540 (395.28 GB)
telemt_user_unique_ips_current{user="hello"} 412
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 65607.7 (18h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 919301
telemt_connections_bad_total 78933
telemt_handshake_timeouts_total 44847
telemt_upstream_connect_attempt_total 168851
telemt_upstream_connect_success_total 168326
telemt_upstream_connect_fail_total 525
telemt_upstream_connect_attempts_per_request{bucket="1"} 168851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12883
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 525
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 54482
telemt_me_reconnect_success_total 12980
telemt_me_reader_eof_total 14633
telemt_me_idle_close_by_peer_total 14633
telemt_me_seq_mismatch_total 25
telemt_me_route_drop_no_conn_total 209487
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 557412
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 42
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1563
telemt_desync_full_logged_total 405
telemt_desync_suppressed_total 1158
telemt_desync_frames_bucket_total{bucket="1_2"} 398
telemt_desync_frames_bucket_total{bucket="3_10"} 622
telemt_desync_frames_bucket_total{bucket="gt_10"} 543
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 14409
telemt_me_refill_failed_total 1298
telemt_me_writer_restored_same_endpoint_total 12944
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1429
telemt_user_connections_total{user="hello"} 709039
telemt_user_connections_current{user="hello"} 945
telemt_user_octets_from_client{user="hello"} 13609727114 (12.68 GB)
telemt_user_octets_to_client{user="hello"} 252790602153 (235.43 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 65608.7 (18h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 930979
telemt_connections_bad_total 12047
telemt_handshake_timeouts_total 20326
telemt_upstream_connect_attempt_total 14668
telemt_upstream_connect_success_total 14588
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 14668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7840
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 14992
telemt_me_reconnect_success_total 11304
telemt_me_reader_eof_total 12053
telemt_me_idle_close_by_peer_total 12053
telemt_me_route_drop_no_conn_total 232213
telemt_me_route_drop_channel_closed_total 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 768565
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2625
telemt_desync_full_logged_total 888
telemt_desync_suppressed_total 1737
telemt_desync_frames_bucket_total{bucket="1_2"} 803
telemt_desync_frames_bucket_total{bucket="3_10"} 997
telemt_desync_frames_bucket_total{bucket="gt_10"} 825
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 11554
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 11296
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 768608
telemt_user_connections_current{user="hello"} 906
telemt_user_octets_from_client{user="hello"} 9452687520 (8.80 GB)
telemt_user_octets_to_client{user="hello"} 274489442028 (255.64 GB)
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 129
```