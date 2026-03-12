# Server Metrics 2026-03-12 07:31:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 5575.7 (1h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164895
telemt_connections_bad_total 1200
telemt_handshake_timeouts_total 1522
telemt_upstream_connect_attempt_total 1176
telemt_upstream_connect_success_total 1168
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 503
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 840
telemt_me_reconnect_success_total 836
telemt_me_reader_eof_total 846
telemt_me_idle_close_by_peer_total 846
telemt_me_route_drop_no_conn_total 55067
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158858
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 804
telemt_desync_full_logged_total 206
telemt_desync_suppressed_total 598
telemt_desync_frames_bucket_total{bucket="1_2"} 180
telemt_desync_frames_bucket_total{bucket="3_10"} 289
telemt_desync_frames_bucket_total{bucket="gt_10"} 335
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 836
telemt_me_writer_restored_same_endpoint_total 823
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_user_connections_total{user="hello"} 158783
telemt_user_connections_current{user="hello"} 1117
telemt_user_octets_from_client{user="hello"} 2620973348 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 47810565636 (44.53 GB)
telemt_user_unique_ips_current{user="hello"} 348
telemt_user_unique_ips_recent_window{user="hello"} 201
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 35196.2 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169860
telemt_connections_bad_total 2327
telemt_handshake_timeouts_total 6627
telemt_upstream_connect_attempt_total 9111
telemt_upstream_connect_success_total 9106
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 9111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4588
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 216
telemt_me_reconnect_attempts_total 7174
telemt_me_reconnect_success_total 7135
telemt_me_reader_eof_total 7586
telemt_me_idle_close_by_peer_total 7586
telemt_me_route_drop_no_conn_total 48707
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 146619
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 407
telemt_desync_full_logged_total 160
telemt_desync_suppressed_total 247
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 145
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 7194
telemt_me_writer_restored_same_endpoint_total 7126
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 146851
telemt_user_connections_current{user="hello"} 532
telemt_user_octets_from_client{user="hello"} 2283373083 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 60275796742 (56.14 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 35196.2 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 528230
telemt_connections_bad_total 2537
telemt_handshake_timeouts_total 39557
telemt_upstream_connect_attempt_total 9377
telemt_upstream_connect_success_total 9375
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 9377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4084
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 7299
telemt_me_reconnect_success_total 7231
telemt_me_reader_eof_total 7583
telemt_me_idle_close_by_peer_total 7583
telemt_me_route_drop_no_conn_total 94993
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 277879
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1237
telemt_desync_full_logged_total 385
telemt_desync_suppressed_total 852
telemt_desync_frames_bucket_total{bucket="1_2"} 151
telemt_desync_frames_bucket_total{bucket="3_10"} 443
telemt_desync_frames_bucket_total{bucket="gt_10"} 643
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 7218
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 7190
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 278168
telemt_user_connections_current{user="hello"} 695
telemt_user_octets_from_client{user="hello"} 2989088564 (2.78 GB)
telemt_user_octets_to_client{user="hello"} 101205813869 (94.26 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 35196.5 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 240238
telemt_connections_bad_total 1778
telemt_handshake_timeouts_total 15064
telemt_upstream_connect_attempt_total 9870
telemt_upstream_connect_success_total 9829
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 9869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4173
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 258
telemt_me_reconnect_attempts_total 8077
telemt_me_reconnect_success_total 8048
telemt_me_reader_eof_total 8545
telemt_me_idle_close_by_peer_total 8545
telemt_me_route_drop_no_conn_total 78452
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 197774
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 340
telemt_desync_full_logged_total 129
telemt_desync_suppressed_total 211
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 124
telemt_desync_frames_bucket_total{bucket="gt_10"} 92
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 8098
telemt_me_writer_restored_same_endpoint_total 8027
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 197641
telemt_user_connections_current{user="hello"} 440
telemt_user_octets_from_client{user="hello"} 2297409788 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 64457269060 (60.03 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 35196.3 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 258869
telemt_connections_bad_total 346
telemt_handshake_timeouts_total 2153
telemt_upstream_connect_attempt_total 11800
telemt_upstream_connect_success_total 11658
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 11800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6048
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5543
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 215
telemt_me_reconnect_attempts_total 11380
telemt_me_reconnect_success_total 9868
telemt_me_reader_eof_total 10278
telemt_me_idle_close_by_peer_total 10278
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 80416
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 242889
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 966
telemt_desync_full_logged_total 322
telemt_desync_suppressed_total 644
telemt_desync_frames_bucket_total{bucket="1_2"} 229
telemt_desync_frames_bucket_total{bucket="3_10"} 360
telemt_desync_frames_bucket_total{bucket="gt_10"} 377
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 10007
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 9847
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 242843
telemt_user_connections_current{user="hello"} 667
telemt_user_octets_from_client{user="hello"} 2338055396 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 57693374076 (53.73 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 109
```