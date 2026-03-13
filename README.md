# Server Metrics 2026-03-13 09:27:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 98948.8 (27h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2818517
telemt_connections_bad_total 36388
telemt_handshake_timeouts_total 40267
telemt_upstream_connect_attempt_total 19410
telemt_upstream_connect_success_total 19302
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 19410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9943
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9310
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_keepalive_timeout_total 1395
telemt_me_reconnect_attempts_total 24466
telemt_me_reconnect_success_total 14405
telemt_me_reader_eof_total 15531
telemt_me_idle_close_by_peer_total 15530
telemt_me_route_drop_no_conn_total 1045443
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2576302
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11338
telemt_desync_full_logged_total 2932
telemt_desync_suppressed_total 8406
telemt_desync_frames_bucket_total{bucket="1_2"} 2909
telemt_desync_frames_bucket_total{bucket="3_10"} 4243
telemt_desync_frames_bucket_total{bucket="gt_10"} 4186
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 14918
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 14392
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 513
telemt_user_connections_total{user="hello"} 2575959
telemt_user_connections_current{user="hello"} 1662
telemt_user_octets_from_client{user="hello"} 35962156804 (33.49 GB)
telemt_user_octets_to_client{user="hello"} 842901378780 (785.01 GB)
telemt_user_unique_ips_current{user="hello"} 443
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 128569.3 (35h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1152123
telemt_connections_bad_total 14389
telemt_handshake_timeouts_total 106046
telemt_upstream_connect_attempt_total 31881
telemt_upstream_connect_success_total 31850
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 31881
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15339
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3688
telemt_me_reconnect_attempts_total 23960
telemt_me_reconnect_success_total 23835
telemt_me_reader_eof_total 25404
telemt_me_idle_close_by_peer_total 25404
telemt_me_route_drop_no_conn_total 353643
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 990158
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4356
telemt_desync_full_logged_total 1322
telemt_desync_suppressed_total 3034
telemt_desync_frames_bucket_total{bucket="1_2"} 1588
telemt_desync_frames_bucket_total{bucket="3_10"} 1437
telemt_desync_frames_bucket_total{bucket="gt_10"} 1331
telemt_pool_swap_total 132
telemt_me_writer_removed_unexpected_total 24069
telemt_me_writer_restored_same_endpoint_total 23826
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 992085
telemt_user_connections_current{user="hello"} 526
telemt_user_octets_from_client{user="hello"} 15163388144 (14.12 GB)
telemt_user_octets_to_client{user="hello"} 364041652307 (339.04 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 128569.1 (35h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2212693
telemt_connections_bad_total 24641
telemt_handshake_timeouts_total 147512
telemt_upstream_connect_attempt_total 29497
telemt_upstream_connect_success_total 29487
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 29497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13916
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1809
telemt_me_reconnect_attempts_total 24038
telemt_me_reconnect_success_total 22752
telemt_me_reader_eof_total 24094
telemt_me_idle_close_by_peer_total 24093
telemt_me_route_drop_no_conn_total 720220
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1770038
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5885
telemt_desync_full_logged_total 1873
telemt_desync_suppressed_total 4012
telemt_desync_frames_bucket_total{bucket="1_2"} 962
telemt_desync_frames_bucket_total{bucket="3_10"} 2147
telemt_desync_frames_bucket_total{bucket="gt_10"} 2776
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 22979
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 22711
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 1769467
telemt_user_connections_current{user="hello"} 883
telemt_user_octets_from_client{user="hello"} 30883062380 (28.76 GB)
telemt_user_octets_to_client{user="hello"} 638574850669 (594.72 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 128569.6 (35h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1403207
telemt_connections_bad_total 14228
telemt_handshake_timeouts_total 85897
telemt_upstream_connect_attempt_total 42399
telemt_upstream_connect_success_total 40094
telemt_upstream_connect_fail_total 2168
telemt_upstream_connect_attempts_per_request{bucket="1"} 42125
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15584
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2167
telemt_me_keepalive_timeout_total 11468
telemt_me_reconnect_attempts_total 36798
telemt_me_reconnect_success_total 27856
telemt_me_reader_eof_total 29996
telemt_me_idle_close_by_peer_total 29989
telemt_me_route_drop_no_conn_total 493711
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1170778
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2211
telemt_desync_full_logged_total 727
telemt_desync_suppressed_total 1484
telemt_desync_frames_bucket_total{bucket="1_2"} 612
telemt_desync_frames_bucket_total{bucket="3_10"} 848
telemt_desync_frames_bucket_total{bucket="gt_10"} 751
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 28336
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 27832
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 480
telemt_user_connections_total{user="hello"} 1175539
telemt_user_connections_current{user="hello"} 654
telemt_user_octets_from_client{user="hello"} 17690880821 (16.48 GB)
telemt_user_octets_to_client{user="hello"} 466294601398 (434.27 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 128569.3 (35h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1563086
telemt_connections_bad_total 35433
telemt_handshake_timeouts_total 12782
telemt_upstream_connect_attempt_total 41145
telemt_upstream_connect_success_total 40654
telemt_upstream_connect_fail_total 491
telemt_upstream_connect_attempts_per_request{bucket="1"} 41145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19955
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 491
telemt_me_keepalive_timeout_total 2207
telemt_me_reconnect_attempts_total 49525
telemt_me_reconnect_success_total 34271
telemt_me_reader_eof_total 35940
telemt_me_idle_close_by_peer_total 35940
telemt_me_seq_mismatch_total 48
telemt_me_route_drop_no_conn_total 571486
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1425728
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 52
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4984
telemt_desync_full_logged_total 1777
telemt_desync_suppressed_total 3207
telemt_desync_frames_bucket_total{bucket="1_2"} 1521
telemt_desync_frames_bucket_total{bucket="3_10"} 1613
telemt_desync_frames_bucket_total{bucket="gt_10"} 1850
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 35124
telemt_me_refill_failed_total 472
telemt_me_writer_restored_same_endpoint_total 34210
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 853
telemt_user_connections_total{user="hello"} 1425529
telemt_user_connections_current{user="hello"} 854
telemt_user_octets_from_client{user="hello"} 18356372400 (17.10 GB)
telemt_user_octets_to_client{user="hello"} 492947457088 (459.09 GB)
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 101
```