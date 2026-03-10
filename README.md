# Server Metrics 2026-03-10 18:39:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 15152.4 (4h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 495961
telemt_connections_bad_total 7985
telemt_handshake_timeouts_total 2401
telemt_upstream_connect_attempt_total 3026
telemt_upstream_connect_success_total 3017
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1457
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1516
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 287
telemt_me_reconnect_attempts_total 12659
telemt_me_reconnect_success_total 2201
telemt_me_reader_eof_total 2508
telemt_me_idle_close_by_peer_total 2508
telemt_me_route_drop_no_conn_total 208623
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 467543
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2376
telemt_desync_full_logged_total 649
telemt_desync_suppressed_total 1727
telemt_desync_frames_bucket_total{bucket="1_2"} 633
telemt_desync_frames_bucket_total{bucket="3_10"} 916
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2536
telemt_me_refill_failed_total 326
telemt_me_writer_restored_same_endpoint_total 2195
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 335
telemt_user_connections_total{user="hello"} 467457
telemt_user_connections_current{user="hello"} 1244
telemt_user_octets_from_client{user="hello"} 6679557420 (6.22 GB)
telemt_user_octets_to_client{user="hello"} 134932153928 (125.67 GB)
telemt_user_unique_ips_current{user="hello"} 336
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 15209.1 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217108
telemt_connections_bad_total 1807
telemt_handshake_timeouts_total 14801
telemt_upstream_connect_attempt_total 8111
telemt_upstream_connect_success_total 5368
telemt_upstream_connect_fail_total 2743
telemt_upstream_connect_attempts_per_request{bucket="1"} 8111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1713
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1620
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1870
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2743
telemt_me_keepalive_timeout_total 692
telemt_me_reconnect_attempts_total 2668
telemt_me_reconnect_success_total 2590
telemt_me_reader_eof_total 2695
telemt_me_idle_close_by_peer_total 2693
telemt_me_route_drop_no_conn_total 125232
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 182931
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 705
telemt_desync_full_logged_total 218
telemt_desync_suppressed_total 487
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 239
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2620
telemt_me_writer_restored_same_endpoint_total 2569
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 184889
telemt_user_connections_current{user="hello"} 405
telemt_user_octets_from_client{user="hello"} 2003428450 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 43635119330 (40.64 GB)
telemt_user_msgs_from_client{user="hello"} 5318
telemt_user_msgs_to_client{user="hello"} 5495
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 15209.0 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 361876
telemt_connections_bad_total 1071
telemt_handshake_timeouts_total 31804
telemt_upstream_connect_attempt_total 4878
telemt_upstream_connect_success_total 4802
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 4878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1886
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 96
telemt_me_reconnect_attempts_total 5055
telemt_me_reconnect_success_total 2954
telemt_me_reader_eof_total 3115
telemt_me_idle_close_by_peer_total 3115
telemt_me_route_drop_no_conn_total 120219
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 304862
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 930
telemt_desync_full_logged_total 265
telemt_desync_suppressed_total 665
telemt_desync_frames_bucket_total{bucket="1_2"} 233
telemt_desync_frames_bucket_total{bucket="3_10"} 313
telemt_desync_frames_bucket_total{bucket="gt_10"} 384
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3072
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 2943
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 305819
telemt_user_connections_current{user="hello"} 751
telemt_user_octets_from_client{user="hello"} 4237985789 (3.95 GB)
telemt_user_octets_to_client{user="hello"} 96579402629 (89.95 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 15209.4 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 234832
telemt_connections_bad_total 14912
telemt_handshake_timeouts_total 21231
telemt_upstream_connect_attempt_total 3906
telemt_upstream_connect_success_total 3906
telemt_upstream_connect_attempts_per_request{bucket="1"} 3906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1822
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 84
telemt_me_reconnect_attempts_total 3133
telemt_me_reconnect_success_total 3114
telemt_me_reader_eof_total 3230
telemt_me_idle_close_by_peer_total 3230
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 77612
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 188918
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 514
telemt_desync_full_logged_total 205
telemt_desync_suppressed_total 309
telemt_desync_frames_bucket_total{bucket="1_2"} 172
telemt_desync_frames_bucket_total{bucket="3_10"} 185
telemt_desync_frames_bucket_total{bucket="gt_10"} 157
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 3142
telemt_me_writer_restored_same_endpoint_total 3102
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 188711
telemt_user_connections_current{user="hello"} 477
telemt_user_octets_from_client{user="hello"} 2830084564 (2.64 GB)
telemt_user_octets_to_client{user="hello"} 53765596916 (50.07 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 15209.3 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 248518
telemt_connections_bad_total 800
telemt_handshake_timeouts_total 1763
telemt_upstream_connect_attempt_total 4566
telemt_upstream_connect_success_total 4551
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 4566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2165
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 3769
telemt_me_reconnect_success_total 3739
telemt_me_reader_eof_total 3852
telemt_me_idle_close_by_peer_total 3852
telemt_me_route_drop_no_conn_total 92143
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234269
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1322
telemt_desync_full_logged_total 469
telemt_desync_suppressed_total 853
telemt_desync_frames_bucket_total{bucket="1_2"} 533
telemt_desync_frames_bucket_total{bucket="3_10"} 555
telemt_desync_frames_bucket_total{bucket="gt_10"} 234
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 3785
telemt_me_writer_restored_same_endpoint_total 3739
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 234202
telemt_user_connections_current{user="hello"} 584
telemt_user_octets_from_client{user="hello"} 4972073016 (4.63 GB)
telemt_user_octets_to_client{user="hello"} 74468396768 (69.35 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 94
```