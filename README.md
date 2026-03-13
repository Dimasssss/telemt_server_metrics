# Server Metrics 2026-03-13 08:57:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 97111.0 (26h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2741809
telemt_connections_bad_total 36356
telemt_handshake_timeouts_total 36836
telemt_upstream_connect_attempt_total 19003
telemt_upstream_connect_success_total 18899
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 19003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9097
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 1371
telemt_me_reconnect_attempts_total 22966
telemt_me_reconnect_success_total 14090
telemt_me_reader_eof_total 15157
telemt_me_idle_close_by_peer_total 15156
telemt_me_route_drop_no_conn_total 1017830
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2505564
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11192
telemt_desync_full_logged_total 2890
telemt_desync_suppressed_total 8302
telemt_desync_frames_bucket_total{bucket="1_2"} 2876
telemt_desync_frames_bucket_total{bucket="3_10"} 4186
telemt_desync_frames_bucket_total{bucket="gt_10"} 4130
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 14561
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 14077
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 471
telemt_user_connections_total{user="hello"} 2505132
telemt_user_connections_current{user="hello"} 1612
telemt_user_octets_from_client{user="hello"} 35259500636 (32.84 GB)
telemt_user_octets_to_client{user="hello"} 825840809096 (769.12 GB)
telemt_user_unique_ips_current{user="hello"} 422
telemt_user_unique_ips_recent_window{user="hello"} 229
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 126731.4 (35h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1120618
telemt_connections_bad_total 14015
telemt_handshake_timeouts_total 98072
telemt_upstream_connect_attempt_total 31521
telemt_upstream_connect_success_total 31490
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 31521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15158
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3633
telemt_me_reconnect_attempts_total 23687
telemt_me_reconnect_success_total 23563
telemt_me_reader_eof_total 25116
telemt_me_idle_close_by_peer_total 25116
telemt_me_route_drop_no_conn_total 343298
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 967396
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4290
telemt_desync_full_logged_total 1306
telemt_desync_suppressed_total 2984
telemt_desync_frames_bucket_total{bucket="1_2"} 1568
telemt_desync_frames_bucket_total{bucket="3_10"} 1412
telemt_desync_frames_bucket_total{bucket="gt_10"} 1310
telemt_pool_swap_total 130
telemt_me_writer_removed_unexpected_total 23795
telemt_me_writer_restored_same_endpoint_total 23554
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 232
telemt_user_connections_total{user="hello"} 969324
telemt_user_connections_current{user="hello"} 561
telemt_user_octets_from_client{user="hello"} 14806511252 (13.79 GB)
telemt_user_octets_to_client{user="hello"} 357340606155 (332.80 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 126731.3 (35h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2168707
telemt_connections_bad_total 24149
telemt_handshake_timeouts_total 144623
telemt_upstream_connect_attempt_total 29084
telemt_upstream_connect_success_total 29074
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 29084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13737
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1764
telemt_me_reconnect_attempts_total 23713
telemt_me_reconnect_success_total 22430
telemt_me_reader_eof_total 23753
telemt_me_idle_close_by_peer_total 23752
telemt_me_route_drop_no_conn_total 703793
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1730947
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5780
telemt_desync_full_logged_total 1831
telemt_desync_suppressed_total 3949
telemt_desync_frames_bucket_total{bucket="1_2"} 947
telemt_desync_frames_bucket_total{bucket="3_10"} 2108
telemt_desync_frames_bucket_total{bucket="gt_10"} 2725
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 22649
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 22389
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 219
telemt_user_connections_total{user="hello"} 1730386
telemt_user_connections_current{user="hello"} 955
telemt_user_octets_from_client{user="hello"} 30342736656 (28.26 GB)
telemt_user_octets_to_client{user="hello"} 627520109829 (584.42 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 126731.8 (35h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1377405
telemt_connections_bad_total 14224
telemt_handshake_timeouts_total 84706
telemt_upstream_connect_attempt_total 42071
telemt_upstream_connect_success_total 39770
telemt_upstream_connect_fail_total 2164
telemt_upstream_connect_attempts_per_request{bucket="1"} 41797
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15441
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2163
telemt_me_keepalive_timeout_total 11454
telemt_me_reconnect_attempts_total 36560
telemt_me_reconnect_success_total 27620
telemt_me_reader_eof_total 29744
telemt_me_idle_close_by_peer_total 29737
telemt_me_route_drop_no_conn_total 483670
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1146818
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2196
telemt_desync_full_logged_total 718
telemt_desync_suppressed_total 1478
telemt_desync_frames_bucket_total{bucket="1_2"} 604
telemt_desync_frames_bucket_total{bucket="3_10"} 845
telemt_desync_frames_bucket_total{bucket="gt_10"} 747
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 28095
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 27596
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 475
telemt_user_connections_total{user="hello"} 1151581
telemt_user_connections_current{user="hello"} 652
telemt_user_octets_from_client{user="hello"} 17320323585 (16.13 GB)
telemt_user_octets_to_client{user="hello"} 457852839178 (426.41 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 126731.5 (35h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1525489
telemt_connections_bad_total 32615
telemt_handshake_timeouts_total 12585
telemt_upstream_connect_attempt_total 40283
telemt_upstream_connect_success_total 39799
telemt_upstream_connect_fail_total 484
telemt_upstream_connect_attempts_per_request{bucket="1"} 40283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19447
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 484
telemt_me_keepalive_timeout_total 2160
telemt_me_reconnect_attempts_total 47254
telemt_me_reconnect_success_total 33507
telemt_me_reader_eof_total 35121
telemt_me_idle_close_by_peer_total 35121
telemt_me_seq_mismatch_total 48
telemt_me_route_drop_no_conn_total 558389
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1396056
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 52
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4891
telemt_desync_full_logged_total 1748
telemt_desync_suppressed_total 3143
telemt_desync_frames_bucket_total{bucket="1_2"} 1492
telemt_desync_frames_bucket_total{bucket="3_10"} 1579
telemt_desync_frames_bucket_total{bucket="gt_10"} 1820
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 34305
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 33446
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 798
telemt_user_connections_total{user="hello"} 1395859
telemt_user_connections_current{user="hello"} 927
telemt_user_octets_from_client{user="hello"} 18103437064 (16.86 GB)
telemt_user_octets_to_client{user="hello"} 485369702052 (452.04 GB)
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 115
```