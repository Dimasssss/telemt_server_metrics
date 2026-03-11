# Server Metrics 2026-03-11 03:33:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 47209.0 (13h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 904555
telemt_connections_bad_total 10070
telemt_handshake_timeouts_total 22878
telemt_upstream_connect_attempt_total 10232
telemt_upstream_connect_success_total 10223
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 10232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5049
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 521
telemt_me_reconnect_attempts_total 19474
telemt_me_reconnect_success_total 7803
telemt_me_reader_eof_total 8515
telemt_me_idle_close_by_peer_total 8515
telemt_me_route_drop_no_conn_total 353701
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 837029
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3877
telemt_desync_full_logged_total 1075
telemt_desync_suppressed_total 2802
telemt_desync_frames_bucket_total{bucket="1_2"} 1102
telemt_desync_frames_bucket_total{bucket="3_10"} 1460
telemt_desync_frames_bucket_total{bucket="gt_10"} 1315
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 8237
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 7797
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 434
telemt_user_connections_total{user="hello"} 836753
telemt_user_connections_current{user="hello"} 618
telemt_user_octets_from_client{user="hello"} 11183679872 (10.42 GB)
telemt_user_octets_to_client{user="hello"} 248848160644 (231.76 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 47265.7 (13h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 372593
telemt_connections_bad_total 2517
telemt_handshake_timeouts_total 18484
telemt_upstream_connect_attempt_total 18256
telemt_upstream_connect_success_total 15364
telemt_upstream_connect_fail_total 2892
telemt_upstream_connect_attempts_per_request{bucket="1"} 18256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6321
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2892
telemt_me_keepalive_timeout_total 1762
telemt_me_reconnect_attempts_total 10846
telemt_me_reconnect_success_total 10029
telemt_me_reader_eof_total 10595
telemt_me_idle_close_by_peer_total 10593
telemt_me_route_drop_no_conn_total 180693
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 319358
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1807
telemt_desync_full_logged_total 528
telemt_desync_suppressed_total 1279
telemt_desync_frames_bucket_total{bucket="1_2"} 554
telemt_desync_frames_bucket_total{bucket="3_10"} 648
telemt_desync_frames_bucket_total{bucket="gt_10"} 605
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 10148
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 10008
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 321624
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 3064969758 (2.85 GB)
telemt_user_octets_to_client{user="hello"} 75690063160 (70.49 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 47265.6 (13h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 624719
telemt_connections_bad_total 5349
telemt_handshake_timeouts_total 34888
telemt_upstream_connect_attempt_total 12797
telemt_upstream_connect_success_total 12631
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 12797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5639
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_keepalive_timeout_total 551
telemt_me_reconnect_attempts_total 20236
telemt_me_reconnect_success_total 9167
telemt_me_reader_eof_total 9946
telemt_me_idle_close_by_peer_total 9946
telemt_me_route_drop_no_conn_total 211894
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 555370
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1606
telemt_desync_full_logged_total 474
telemt_desync_suppressed_total 1132
telemt_desync_frames_bucket_total{bucket="1_2"} 351
telemt_desync_frames_bucket_total{bucket="3_10"} 561
telemt_desync_frames_bucket_total{bucket="gt_10"} 694
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 9635
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 9156
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 468
telemt_user_connections_total{user="hello"} 556264
telemt_user_connections_current{user="hello"} 298
telemt_user_octets_from_client{user="hello"} 7125931757 (6.64 GB)
telemt_user_octets_to_client{user="hello"} 169246609705 (157.62 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 47266.0 (13h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 471317
telemt_connections_bad_total 44623
telemt_handshake_timeouts_total 46625
telemt_upstream_connect_attempt_total 13799
telemt_upstream_connect_success_total 13799
telemt_upstream_connect_attempts_per_request{bucket="1"} 13799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6003
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 472
telemt_me_reconnect_attempts_total 12452
telemt_me_reconnect_success_total 11414
telemt_me_reader_eof_total 12117
telemt_me_idle_close_by_peer_total 12117
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 140484
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 366243
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 785
telemt_desync_full_logged_total 311
telemt_desync_suppressed_total 474
telemt_desync_frames_bucket_total{bucket="1_2"} 291
telemt_desync_frames_bucket_total{bucket="3_10"} 277
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 11548
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 11395
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 365910
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 4473932532 (4.17 GB)
telemt_user_octets_to_client{user="hello"} 97431444892 (90.74 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 47265.5 (13h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 497956
telemt_connections_bad_total 5811
telemt_handshake_timeouts_total 3100
telemt_upstream_connect_attempt_total 13844
telemt_upstream_connect_success_total 13786
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 13844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7097
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6567
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 539
telemt_me_reconnect_attempts_total 15136
telemt_me_reconnect_success_total 11356
telemt_me_reader_eof_total 11985
telemt_me_idle_close_by_peer_total 11985
telemt_me_route_drop_no_conn_total 159476
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 453241
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2339
telemt_desync_full_logged_total 914
telemt_desync_suppressed_total 1425
telemt_desync_frames_bucket_total{bucket="1_2"} 867
telemt_desync_frames_bucket_total{bucket="3_10"} 993
telemt_desync_frames_bucket_total{bucket="gt_10"} 479
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 11618
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 11356
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 262
telemt_user_connections_total{user="hello"} 452887
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 8618106424 (8.03 GB)
telemt_user_octets_to_client{user="hello"} 162128579292 (150.99 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 35
```