# Server Metrics 2026-03-12 13:23:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 26686.3 (7h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 925459
telemt_connections_bad_total 5608
telemt_handshake_timeouts_total 8468
telemt_upstream_connect_attempt_total 5222
telemt_upstream_connect_success_total 5190
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 5222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2380
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 7722
telemt_me_reconnect_success_total 3824
telemt_me_reader_eof_total 4105
telemt_me_idle_close_by_peer_total 4104
telemt_me_route_drop_no_conn_total 327995
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 884902
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4720
telemt_desync_full_logged_total 1192
telemt_desync_suppressed_total 3528
telemt_desync_frames_bucket_total{bucket="1_2"} 1175
telemt_desync_frames_bucket_total{bucket="3_10"} 1723
telemt_desync_frames_bucket_total{bucket="gt_10"} 1822
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3989
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3811
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 884720
telemt_user_connections_current{user="hello"} 1523
telemt_user_octets_from_client{user="hello"} 14605890756 (13.60 GB)
telemt_user_octets_to_client{user="hello"} 264615189516 (246.44 GB)
telemt_user_unique_ips_current{user="hello"} 417
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 56306.8 (15h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 453769
telemt_connections_bad_total 5284
telemt_handshake_timeouts_total 24587
telemt_upstream_connect_attempt_total 13629
telemt_upstream_connect_success_total 13622
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 13629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6908
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1083
telemt_me_reconnect_attempts_total 10687
telemt_me_reconnect_success_total 10629
telemt_me_reader_eof_total 11300
telemt_me_idle_close_by_peer_total 11300
telemt_me_route_drop_no_conn_total 130568
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 400999
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1365
telemt_desync_full_logged_total 443
telemt_desync_suppressed_total 922
telemt_desync_frames_bucket_total{bucket="1_2"} 555
telemt_desync_frames_bucket_total{bucket="3_10"} 470
telemt_desync_frames_bucket_total{bucket="gt_10"} 340
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 10725
telemt_me_writer_restored_same_endpoint_total 10620
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 401465
telemt_user_connections_current{user="hello"} 703
telemt_user_octets_from_client{user="hello"} 6282497243 (5.85 GB)
telemt_user_octets_to_client{user="hello"} 145230449054 (135.26 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 56306.8 (15h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 998837
telemt_connections_bad_total 5443
telemt_handshake_timeouts_total 75546
telemt_upstream_connect_attempt_total 13572
telemt_upstream_connect_success_total 13567
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 13572
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6118
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 868
telemt_me_reconnect_attempts_total 10489
telemt_me_reconnect_success_total 10396
telemt_me_reader_eof_total 10952
telemt_me_idle_close_by_peer_total 10952
telemt_me_route_drop_no_conn_total 253077
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 699732
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3055
telemt_desync_full_logged_total 924
telemt_desync_suppressed_total 2131
telemt_desync_frames_bucket_total{bucket="1_2"} 436
telemt_desync_frames_bucket_total{bucket="3_10"} 1097
telemt_desync_frames_bucket_total{bucket="gt_10"} 1522
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 10429
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 10355
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 699952
telemt_user_connections_current{user="hello"} 967
telemt_user_octets_from_client{user="hello"} 9234098320 (8.60 GB)
telemt_user_octets_to_client{user="hello"} 227334195257 (211.72 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 56307.1 (15h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 568237
telemt_connections_bad_total 7665
telemt_handshake_timeouts_total 52997
telemt_upstream_connect_attempt_total 15029
telemt_upstream_connect_success_total 14968
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 15029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6451
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 1288
telemt_me_reconnect_attempts_total 13386
telemt_me_reconnect_success_total 12153
telemt_me_reader_eof_total 12895
telemt_me_idle_close_by_peer_total 12895
telemt_me_route_drop_no_conn_total 190787
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 476824
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 961
telemt_desync_full_logged_total 336
telemt_desync_suppressed_total 625
telemt_desync_frames_bucket_total{bucket="1_2"} 276
telemt_desync_frames_bucket_total{bucket="3_10"} 394
telemt_desync_frames_bucket_total{bucket="gt_10"} 291
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12284
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 12132
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 476333
telemt_user_connections_current{user="hello"} 727
telemt_user_octets_from_client{user="hello"} 5385316908 (5.02 GB)
telemt_user_octets_to_client{user="hello"} 192840085408 (179.60 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 56307.0 (15h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 641565
telemt_connections_bad_total 1736
telemt_handshake_timeouts_total 5214
telemt_upstream_connect_attempt_total 17945
telemt_upstream_connect_success_total 17727
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 17945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9009
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8619
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 22133
telemt_me_reconnect_success_total 14906
telemt_me_reader_eof_total 15633
telemt_me_idle_close_by_peer_total 15633
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 218280
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 597300
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2490
telemt_desync_full_logged_total 839
telemt_desync_suppressed_total 1651
telemt_desync_frames_bucket_total{bucket="1_2"} 688
telemt_desync_frames_bucket_total{bucket="3_10"} 882
telemt_desync_frames_bucket_total{bucket="gt_10"} 920
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 15277
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 14878
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 371
telemt_user_connections_total{user="hello"} 597211
telemt_user_connections_current{user="hello"} 833
telemt_user_octets_from_client{user="hello"} 6870516820 (6.40 GB)
telemt_user_octets_to_client{user="hello"} 159081743944 (148.16 GB)
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 107
```