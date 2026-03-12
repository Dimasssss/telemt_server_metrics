# Server Metrics 2026-03-12 21:13:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 54872.8 (15h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1850683
telemt_connections_bad_total 22950
telemt_handshake_timeouts_total 20319
telemt_upstream_connect_attempt_total 10651
telemt_upstream_connect_success_total 10590
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 10651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5043
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 585
telemt_me_reconnect_attempts_total 16688
telemt_me_reconnect_success_total 7836
telemt_me_reader_eof_total 8474
telemt_me_idle_close_by_peer_total 8473
telemt_me_route_drop_no_conn_total 726697
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1725335
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8374
telemt_desync_full_logged_total 2165
telemt_desync_suppressed_total 6209
telemt_desync_frames_bucket_total{bucket="1_2"} 2197
telemt_desync_frames_bucket_total{bucket="3_10"} 3022
telemt_desync_frames_bucket_total{bucket="gt_10"} 3155
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 8225
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 7823
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 389
telemt_user_connections_total{user="hello"} 1724818
telemt_user_connections_current{user="hello"} 989
telemt_user_octets_from_client{user="hello"} 26404265468 (24.59 GB)
telemt_user_octets_to_client{user="hello"} 606906401708 (565.23 GB)
telemt_user_unique_ips_current{user="hello"} 297
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 84493.3 (23h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 773661
telemt_connections_bad_total 11621
telemt_handshake_timeouts_total 30608
telemt_upstream_connect_attempt_total 21335
telemt_upstream_connect_success_total 21306
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 21335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9967
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3392
telemt_me_reconnect_attempts_total 15537
telemt_me_reconnect_success_total 15445
telemt_me_reader_eof_total 16424
telemt_me_idle_close_by_peer_total 16424
telemt_me_route_drop_no_conn_total 250545
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 697970
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2970
telemt_desync_full_logged_total 916
telemt_desync_suppressed_total 2054
telemt_desync_frames_bucket_total{bucket="1_2"} 1165
telemt_desync_frames_bucket_total{bucket="3_10"} 978
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 15602
telemt_me_writer_restored_same_endpoint_total 15436
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 699848
telemt_user_connections_current{user="hello"} 310
telemt_user_octets_from_client{user="hello"} 11906057268 (11.09 GB)
telemt_user_octets_to_client{user="hello"} 269319647323 (250.82 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 84492.9 (23h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1600957
telemt_connections_bad_total 7556
telemt_handshake_timeouts_total 110631
telemt_upstream_connect_attempt_total 19782
telemt_upstream_connect_success_total 19776
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 19782
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9084
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1211
telemt_me_reconnect_attempts_total 16452
telemt_me_reconnect_success_total 15205
telemt_me_reader_eof_total 16051
telemt_me_idle_close_by_peer_total 16050
telemt_me_route_drop_no_conn_total 529163
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1238437
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4863
telemt_desync_full_logged_total 1495
telemt_desync_suppressed_total 3368
telemt_desync_frames_bucket_total{bucket="1_2"} 771
telemt_desync_frames_bucket_total{bucket="3_10"} 1756
telemt_desync_frames_bucket_total{bucket="gt_10"} 2336
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 15348
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 15164
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 1238044
telemt_user_connections_current{user="hello"} 603
telemt_user_octets_from_client{user="hello"} 19396622240 (18.06 GB)
telemt_user_octets_to_client{user="hello"} 460075581613 (428.48 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 84493.7 (23h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 985047
telemt_connections_bad_total 12974
telemt_handshake_timeouts_total 70947
telemt_upstream_connect_attempt_total 21516
telemt_upstream_connect_success_total 21428
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 21516
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9379
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 1675
telemt_me_reconnect_attempts_total 24947
telemt_me_reconnect_success_total 17219
telemt_me_reader_eof_total 18389
telemt_me_idle_close_by_peer_total 18389
telemt_me_route_drop_no_conn_total 352230
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 857189
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1837
telemt_desync_full_logged_total 610
telemt_desync_suppressed_total 1227
telemt_desync_frames_bucket_total{bucket="1_2"} 511
telemt_desync_frames_bucket_total{bucket="3_10"} 711
telemt_desync_frames_bucket_total{bucket="gt_10"} 615
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 17598
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 17198
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 379
telemt_user_connections_total{user="hello"} 856539
telemt_user_connections_current{user="hello"} 383
telemt_user_octets_from_client{user="hello"} 13429298276 (12.51 GB)
telemt_user_octets_to_client{user="hello"} 347084251868 (323.25 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 84493.4 (23h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1104640
telemt_connections_bad_total 12513
telemt_handshake_timeouts_total 9026
telemt_upstream_connect_attempt_total 26124
telemt_upstream_connect_success_total 25803
telemt_upstream_connect_fail_total 321
telemt_upstream_connect_attempts_per_request{bucket="1"} 26124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13205
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12454
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 321
telemt_me_keepalive_timeout_total 1429
telemt_me_reconnect_attempts_total 32617
telemt_me_reconnect_success_total 21579
telemt_me_reader_eof_total 22669
telemt_me_idle_close_by_peer_total 22669
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 414214
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1015019
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3851
telemt_desync_full_logged_total 1341
telemt_desync_suppressed_total 2510
telemt_desync_frames_bucket_total{bucket="1_2"} 1124
telemt_desync_frames_bucket_total{bucket="3_10"} 1275
telemt_desync_frames_bucket_total{bucket="gt_10"} 1452
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 22171
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 21535
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 592
telemt_user_connections_total{user="hello"} 1014879
telemt_user_connections_current{user="hello"} 443
telemt_user_octets_from_client{user="hello"} 12540565360 (11.68 GB)
telemt_user_octets_to_client{user="hello"} 358749326844 (334.11 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 55
```