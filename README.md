# Server Metrics 2026-03-10 22:39:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 29532.7 (8h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 740092
telemt_connections_bad_total 8946
telemt_handshake_timeouts_total 8357
telemt_upstream_connect_attempt_total 6334
telemt_upstream_connect_success_total 6325
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 6334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3129
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 360
telemt_me_reconnect_attempts_total 16441
telemt_me_reconnect_success_total 4781
telemt_me_reader_eof_total 5273
telemt_me_idle_close_by_peer_total 5273
telemt_me_route_drop_no_conn_total 308203
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 699919
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3468
telemt_desync_full_logged_total 967
telemt_desync_suppressed_total 2501
telemt_desync_frames_bucket_total{bucket="1_2"} 999
telemt_desync_frames_bucket_total{bucket="3_10"} 1298
telemt_desync_frames_bucket_total{bucket="gt_10"} 1171
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 5185
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 4775
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 404
telemt_user_connections_total{user="hello"} 699721
telemt_user_connections_current{user="hello"} 499
telemt_user_octets_from_client{user="hello"} 10020297928 (9.33 GB)
telemt_user_octets_to_client{user="hello"} 211642835648 (197.11 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 29589.5 (8h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 320764
telemt_connections_bad_total 2363
telemt_handshake_timeouts_total 17581
telemt_upstream_connect_attempt_total 12985
telemt_upstream_connect_success_total 10118
telemt_upstream_connect_fail_total 2867
telemt_upstream_connect_attempts_per_request{bucket="1"} 12985
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3604
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2867
telemt_me_keepalive_timeout_total 1378
telemt_me_reconnect_attempts_total 6466
telemt_me_reconnect_success_total 5660
telemt_me_reader_eof_total 5930
telemt_me_idle_close_by_peer_total 5928
telemt_me_route_drop_no_conn_total 167221
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 270784
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1634
telemt_desync_full_logged_total 453
telemt_desync_suppressed_total 1181
telemt_desync_frames_bucket_total{bucket="1_2"} 498
telemt_desync_frames_bucket_total{bucket="3_10"} 580
telemt_desync_frames_bucket_total{bucket="gt_10"} 556
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 5749
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 5639
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 273057
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 2670083206 (2.49 GB)
telemt_user_octets_to_client{user="hello"} 64324416368 (59.91 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 29589.4 (8h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 530377
telemt_connections_bad_total 3449
telemt_handshake_timeouts_total 33838
telemt_upstream_connect_attempt_total 8107
telemt_upstream_connect_success_total 7988
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 8107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3310
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 214
telemt_me_reconnect_attempts_total 16459
telemt_me_reconnect_success_total 5404
telemt_me_reader_eof_total 5940
telemt_me_idle_close_by_peer_total 5940
telemt_me_route_drop_no_conn_total 183882
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 464747
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1499
telemt_desync_full_logged_total 423
telemt_desync_suppressed_total 1076
telemt_desync_frames_bucket_total{bucket="1_2"} 336
telemt_desync_frames_bucket_total{bucket="3_10"} 519
telemt_desync_frames_bucket_total{bucket="gt_10"} 644
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 5834
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 5393
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 430
telemt_user_connections_total{user="hello"} 465679
telemt_user_connections_current{user="hello"} 236
telemt_user_octets_from_client{user="hello"} 6645383509 (6.19 GB)
telemt_user_octets_to_client{user="hello"} 148525091765 (138.32 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 29589.8 (8h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 373641
telemt_connections_bad_total 28469
telemt_handshake_timeouts_total 33514
telemt_upstream_connect_attempt_total 8177
telemt_upstream_connect_success_total 8177
telemt_upstream_connect_attempts_per_request{bucket="1"} 8177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3656
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 175
telemt_me_reconnect_attempts_total 7691
telemt_me_reconnect_success_total 6667
telemt_me_reader_eof_total 7009
telemt_me_idle_close_by_peer_total 7009
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 119454
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 298768
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 687
telemt_desync_full_logged_total 279
telemt_desync_suppressed_total 408
telemt_desync_frames_bucket_total{bucket="1_2"} 266
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 6769
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 6653
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 298443
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 4053228992 (3.77 GB)
telemt_user_octets_to_client{user="hello"} 87206186648 (81.22 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 29589.4 (8h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 394198
telemt_connections_bad_total 2541
telemt_handshake_timeouts_total 2583
telemt_upstream_connect_attempt_total 9114
telemt_upstream_connect_success_total 9078
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 9114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4755
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4214
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 198
telemt_me_reconnect_attempts_total 11294
telemt_me_reconnect_success_total 7535
telemt_me_reader_eof_total 7904
telemt_me_idle_close_by_peer_total 7904
telemt_me_route_drop_no_conn_total 137497
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 367083
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2149
telemt_desync_full_logged_total 824
telemt_desync_suppressed_total 1325
telemt_desync_frames_bucket_total{bucket="1_2"} 796
telemt_desync_frames_bucket_total{bucket="3_10"} 919
telemt_desync_frames_bucket_total{bucket="gt_10"} 434
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 7757
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 7535
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 366906
telemt_user_connections_current{user="hello"} 308
telemt_user_octets_from_client{user="hello"} 6434185380 (5.99 GB)
telemt_user_octets_to_client{user="hello"} 137849874796 (128.38 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 53
```