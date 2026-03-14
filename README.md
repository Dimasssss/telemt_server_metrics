# Server Metrics 2026-03-14 02:39:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 160863.5 (44h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4676598
telemt_connections_bad_total 39820
telemt_handshake_timeouts_total 108476
telemt_upstream_connect_attempt_total 33987
telemt_upstream_connect_success_total 33761
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 33987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18422
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15193
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_keepalive_timeout_total 6725
telemt_me_reconnect_attempts_total 33559
telemt_me_reconnect_success_total 23418
telemt_me_reader_eof_total 25117
telemt_me_idle_close_by_peer_total 25116
telemt_me_route_drop_no_conn_total 1778077
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4288754
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16759
telemt_desync_full_logged_total 4521
telemt_desync_suppressed_total 12238
telemt_desync_frames_bucket_total{bucket="1_2"} 4188
telemt_desync_frames_bucket_total{bucket="3_10"} 6394
telemt_desync_frames_bucket_total{bucket="gt_10"} 6177
telemt_pool_swap_total 138
telemt_me_writer_removed_unexpected_total 24073
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 23405
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 655
telemt_user_connections_total{user="hello"} 4290360
telemt_user_connections_current{user="hello"} 640
telemt_user_octets_from_client{user="hello"} 62963261692 (58.64 GB)
telemt_user_octets_to_client{user="hello"} 1355872438201 (1.23 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 60527.0 (16h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 698413
telemt_connections_bad_total 50973
telemt_handshake_timeouts_total 13116
telemt_upstream_connect_attempt_total 16931
telemt_upstream_connect_success_total 16679
telemt_upstream_connect_fail_total 252
telemt_upstream_connect_attempts_per_request{bucket="1"} 16931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7131
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 252
telemt_me_keepalive_timeout_total 2060
telemt_me_reconnect_attempts_total 15057
telemt_me_reconnect_success_total 11612
telemt_me_reader_eof_total 12329
telemt_me_idle_close_by_peer_total 12328
telemt_me_route_drop_no_conn_total 234815
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 559292
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1684
telemt_desync_full_logged_total 463
telemt_desync_suppressed_total 1221
telemt_desync_frames_bucket_total{bucket="1_2"} 360
telemt_desync_frames_bucket_total{bucket="3_10"} 733
telemt_desync_frames_bucket_total{bucket="gt_10"} 591
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 11878
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 11604
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 266
telemt_user_connections_total{user="hello"} 561243
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 5990700773 (5.58 GB)
telemt_user_octets_to_client{user="hello"} 180370492096 (167.98 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 190483.7 (52h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3379450
telemt_connections_bad_total 34991
telemt_handshake_timeouts_total 223391
telemt_upstream_connect_attempt_total 42921
telemt_upstream_connect_success_total 42900
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 42921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20127
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 231
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10424
telemt_me_reconnect_attempts_total 38073
telemt_me_reconnect_success_total 33111
telemt_me_reader_eof_total 35163
telemt_me_idle_close_by_peer_total 35162
telemt_me_route_drop_no_conn_total 1158262
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2812661
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9349
telemt_desync_full_logged_total 3123
telemt_desync_suppressed_total 6226
telemt_desync_frames_bucket_total{bucket="1_2"} 1610
telemt_desync_frames_bucket_total{bucket="3_10"} 3382
telemt_desync_frames_bucket_total{bucket="gt_10"} 4357
telemt_pool_swap_total 179
telemt_me_writer_removed_unexpected_total 33575
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 33070
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 2811885
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 45192903192 (42.09 GB)
telemt_user_octets_to_client{user="hello"} 1005299361997 (936.26 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 190486.3 (52h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2257783
telemt_connections_bad_total 22970
telemt_handshake_timeouts_total 246923
telemt_upstream_connect_attempt_total 59709
telemt_upstream_connect_success_total 57246
telemt_upstream_connect_fail_total 2326
telemt_upstream_connect_attempts_per_request{bucket="1"} 59435
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22868
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2325
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20423
telemt_me_reconnect_attempts_total 49778
telemt_me_reconnect_success_total 40745
telemt_me_reader_eof_total 43697
telemt_me_idle_close_by_peer_total 43690
telemt_me_route_drop_no_conn_total 772089
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1801283
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3806
telemt_desync_full_logged_total 1223
telemt_desync_suppressed_total 2583
telemt_desync_frames_bucket_total{bucket="1_2"} 1012
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 167
telemt_me_writer_removed_unexpected_total 41379
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 40721
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 634
telemt_user_connections_total{user="hello"} 1807212
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 27608064967 (25.71 GB)
telemt_user_octets_to_client{user="hello"} 666806433446 (621.01 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 59919.7 (16h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 699093
telemt_connections_bad_total 7911
telemt_handshake_timeouts_total 8663
telemt_upstream_connect_attempt_total 15303
telemt_upstream_connect_success_total 14886
telemt_upstream_connect_fail_total 417
telemt_upstream_connect_attempts_per_request{bucket="1"} 15303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7695
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 417
telemt_me_keepalive_timeout_total 1504
telemt_me_reconnect_attempts_total 44049
telemt_me_reconnect_success_total 11886
telemt_me_reader_eof_total 13197
telemt_me_idle_close_by_peer_total 13196
telemt_me_route_drop_no_conn_total 265455
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 651153
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1698
telemt_desync_full_logged_total 532
telemt_desync_suppressed_total 1166
telemt_desync_frames_bucket_total{bucket="1_2"} 511
telemt_desync_frames_bucket_total{bucket="3_10"} 657
telemt_desync_frames_bucket_total{bucket="gt_10"} 530
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 12995
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 11881
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1109
telemt_user_connections_total{user="hello"} 651035
telemt_user_connections_current{user="hello"} 305
telemt_user_octets_from_client{user="hello"} 11921047556 (11.10 GB)
telemt_user_octets_to_client{user="hello"} 211905793708 (197.35 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 35
```