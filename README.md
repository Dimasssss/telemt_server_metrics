# Server Metrics 2026-03-13 22:03:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 144300.8 (40h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4510330
telemt_connections_bad_total 38271
telemt_handshake_timeouts_total 106867
telemt_upstream_connect_attempt_total 30156
telemt_upstream_connect_success_total 29948
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 30156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13361
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_keepalive_timeout_total 6622
telemt_me_reconnect_attempts_total 30530
telemt_me_reconnect_success_total 20410
telemt_me_reader_eof_total 21903
telemt_me_idle_close_by_peer_total 21902
telemt_me_route_drop_no_conn_total 1702511
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4132582
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16458
telemt_desync_full_logged_total 4415
telemt_desync_suppressed_total 12043
telemt_desync_frames_bucket_total{bucket="1_2"} 4099
telemt_desync_frames_bucket_total{bucket="3_10"} 6288
telemt_desync_frames_bucket_total{bucket="gt_10"} 6071
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 21021
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 20397
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 611
telemt_user_connections_total{user="hello"} 4134711
telemt_user_connections_current{user="hello"} 741
telemt_user_octets_from_client{user="hello"} 60777179932 (56.60 GB)
telemt_user_octets_to_client{user="hello"} 1308352440133 (1.19 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 43964.5 (12h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 584612
telemt_connections_bad_total 41529
telemt_handshake_timeouts_total 12375
telemt_upstream_connect_attempt_total 12404
telemt_upstream_connect_success_total 12180
telemt_upstream_connect_fail_total 224
telemt_upstream_connect_attempts_per_request{bucket="1"} 12404
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4899
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 202
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 224
telemt_me_keepalive_timeout_total 1903
telemt_me_reconnect_attempts_total 11381
telemt_me_reconnect_success_total 7953
telemt_me_reader_eof_total 8418
telemt_me_idle_close_by_peer_total 8417
telemt_me_route_drop_no_conn_total 213919
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 507193
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1643
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 712
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 8173
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 7945
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 220
telemt_user_connections_total{user="hello"} 509124
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 5532845645 (5.15 GB)
telemt_user_octets_to_client{user="hello"} 166260558164 (154.84 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 173921.3 (48h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3279880
telemt_connections_bad_total 31412
telemt_handshake_timeouts_total 219599
telemt_upstream_connect_attempt_total 38579
telemt_upstream_connect_success_total 38558
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 38579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18217
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 218
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10273
telemt_me_reconnect_attempts_total 34512
telemt_me_reconnect_success_total 29561
telemt_me_reader_eof_total 31375
telemt_me_idle_close_by_peer_total 31374
telemt_me_route_drop_no_conn_total 1123239
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2722446
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8933
telemt_desync_full_logged_total 3001
telemt_desync_suppressed_total 5932
telemt_desync_frames_bucket_total{bucket="1_2"} 1473
telemt_desync_frames_bucket_total{bucket="3_10"} 3252
telemt_desync_frames_bucket_total{bucket="gt_10"} 4208
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 29997
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 29520
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 436
telemt_user_connections_total{user="hello"} 2721711
telemt_user_connections_current{user="hello"} 471
telemt_user_octets_from_client{user="hello"} 44517386948 (41.46 GB)
telemt_user_octets_to_client{user="hello"} 962268343261 (896.18 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 173923.8 (48h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2137831
telemt_connections_bad_total 22813
telemt_handshake_timeouts_total 214082
telemt_upstream_connect_attempt_total 54145
telemt_upstream_connect_success_total 51698
telemt_upstream_connect_fail_total 2310
telemt_upstream_connect_attempts_per_request{bucket="1"} 53871
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2309
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20307
telemt_me_reconnect_attempts_total 45012
telemt_me_reconnect_success_total 35997
telemt_me_reader_eof_total 38628
telemt_me_idle_close_by_peer_total 38621
telemt_me_route_drop_no_conn_total 751557
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1750104
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3791
telemt_desync_full_logged_total 1213
telemt_desync_suppressed_total 2578
telemt_desync_frames_bucket_total{bucket="1_2"} 1000
telemt_desync_frames_bucket_total{bucket="3_10"} 1585
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 152
telemt_me_writer_removed_unexpected_total 36590
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 35973
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 593
telemt_user_connections_total{user="hello"} 1755985
telemt_user_connections_current{user="hello"} 262
telemt_user_octets_from_client{user="hello"} 27262475239 (25.39 GB)
telemt_user_octets_to_client{user="hello"} 656991836630 (611.87 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 43357.4 (12h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 624994
telemt_connections_bad_total 5846
telemt_handshake_timeouts_total 5741
telemt_upstream_connect_attempt_total 9857
telemt_upstream_connect_success_total 9538
telemt_upstream_connect_fail_total 319
telemt_upstream_connect_attempts_per_request{bucket="1"} 9857
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4922
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 319
telemt_me_keepalive_timeout_total 980
telemt_me_reconnect_attempts_total 33562
telemt_me_reconnect_success_total 7340
telemt_me_reader_eof_total 8294
telemt_me_idle_close_by_peer_total 8293
telemt_me_route_drop_no_conn_total 238105
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585431
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1562
telemt_desync_full_logged_total 486
telemt_desync_suppressed_total 1076
telemt_desync_frames_bucket_total{bucket="1_2"} 474
telemt_desync_frames_bucket_total{bucket="3_10"} 612
telemt_desync_frames_bucket_total{bucket="gt_10"} 476
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 8224
telemt_me_refill_failed_total 816
telemt_me_writer_restored_same_endpoint_total 7335
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 884
telemt_user_connections_total{user="hello"} 585343
telemt_user_connections_current{user="hello"} 426
telemt_user_octets_from_client{user="hello"} 8587641976 (8.00 GB)
telemt_user_octets_to_client{user="hello"} 186709030124 (173.89 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 53
```