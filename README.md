# Server Metrics 2026-03-14 12:28:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 196165.0 (54h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5693131
telemt_connections_bad_total 61684
telemt_handshake_timeouts_total 125581
telemt_upstream_connect_attempt_total 41162
telemt_upstream_connect_success_total 40899
telemt_upstream_connect_fail_total 263
telemt_upstream_connect_attempts_per_request{bucket="1"} 41162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18598
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 263
telemt_me_keepalive_timeout_total 7849
telemt_me_reconnect_attempts_total 45196
telemt_me_reconnect_success_total 28819
telemt_me_reader_eof_total 30997
telemt_me_idle_close_by_peer_total 30996
telemt_me_route_drop_no_conn_total 2157530
telemt_me_route_drop_channel_closed_total 31
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5221469
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 20168
telemt_desync_full_logged_total 5514
telemt_desync_suppressed_total 14654
telemt_desync_frames_bucket_total{bucket="1_2"} 4869
telemt_desync_frames_bucket_total{bucket="3_10"} 7672
telemt_desync_frames_bucket_total{bucket="gt_10"} 7627
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 29747
telemt_me_refill_failed_total 506
telemt_me_writer_restored_same_endpoint_total 28806
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 928
telemt_user_connections_total{user="hello"} 5223044
telemt_user_connections_current{user="hello"} 1836
telemt_user_octets_from_client{user="hello"} 81101938560 (75.53 GB)
telemt_user_octets_to_client{user="hello"} 1662682889893 (1.51 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 496
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 95829.0 (26h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1103754
telemt_connections_bad_total 58960
telemt_handshake_timeouts_total 25759
telemt_upstream_connect_attempt_total 24609
telemt_upstream_connect_success_total 24302
telemt_upstream_connect_fail_total 307
telemt_upstream_connect_attempts_per_request{bucket="1"} 24609
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10760
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 264
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 307
telemt_me_keepalive_timeout_total 2408
telemt_me_reconnect_attempts_total 36590
telemt_me_reconnect_success_total 17492
telemt_me_reader_eof_total 18979
telemt_me_idle_close_by_peer_total 18978
telemt_me_route_drop_no_conn_total 373909
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 910733
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2526
telemt_desync_full_logged_total 795
telemt_desync_suppressed_total 1731
telemt_desync_frames_bucket_total{bucket="1_2"} 654
telemt_desync_frames_bucket_total{bucket="3_10"} 1050
telemt_desync_frames_bucket_total{bucket="gt_10"} 822
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18335
telemt_me_refill_failed_total 590
telemt_me_writer_restored_same_endpoint_total 17484
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 843
telemt_user_connections_total{user="hello"} 912644
telemt_user_connections_current{user="hello"} 591
telemt_user_octets_from_client{user="hello"} 9984532637 (9.30 GB)
telemt_user_octets_to_client{user="hello"} 322824129392 (300.65 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 225785.6 (62h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4038451
telemt_connections_bad_total 46565
telemt_handshake_timeouts_total 278377
telemt_upstream_connect_attempt_total 50776
telemt_upstream_connect_success_total 50755
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 50776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26774
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23715
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 259
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11272
telemt_me_reconnect_attempts_total 45206
telemt_me_reconnect_success_total 39204
telemt_me_reader_eof_total 41642
telemt_me_idle_close_by_peer_total 41640
telemt_me_route_drop_no_conn_total 1387685
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3377456
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10823
telemt_desync_full_logged_total 3655
telemt_desync_suppressed_total 7168
telemt_desync_frames_bucket_total{bucket="1_2"} 1979
telemt_desync_frames_bucket_total{bucket="3_10"} 3904
telemt_desync_frames_bucket_total{bucket="gt_10"} 4940
telemt_pool_swap_total 209
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 39783
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 39163
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 579
telemt_user_connections_total{user="hello"} 3376596
telemt_user_connections_current{user="hello"} 912
telemt_user_octets_from_client{user="hello"} 57716713652 (53.75 GB)
telemt_user_octets_to_client{user="hello"} 1204053167453 (1.10 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 225788.3 (62h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2636028
telemt_connections_bad_total 23515
telemt_handshake_timeouts_total 340771
telemt_upstream_connect_attempt_total 69592
telemt_upstream_connect_success_total 67083
telemt_upstream_connect_fail_total 2372
telemt_upstream_connect_attempts_per_request{bucket="1"} 69318
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27001
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2371
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20964
telemt_me_reconnect_attempts_total 61609
telemt_me_reconnect_success_total 48826
telemt_me_reader_eof_total 52307
telemt_me_idle_close_by_peer_total 52299
telemt_me_route_drop_no_conn_total 875299
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2060098
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4117
telemt_desync_full_logged_total 1355
telemt_desync_suppressed_total 2762
telemt_desync_frames_bucket_total{bucket="1_2"} 1171
telemt_desync_frames_bucket_total{bucket="3_10"} 1683
telemt_desync_frames_bucket_total{bucket="gt_10"} 1263
telemt_pool_swap_total 193
telemt_me_writer_removed_unexpected_total 49651
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 48801
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 825
telemt_user_connections_total{user="hello"} 2066566
telemt_user_connections_current{user="hello"} 446
telemt_user_octets_from_client{user="hello"} 30564911003 (28.47 GB)
telemt_user_octets_to_client{user="hello"} 735057976278 (684.58 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 95221.8 (26h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1090986
telemt_connections_bad_total 18126
telemt_handshake_timeouts_total 13992
telemt_upstream_connect_attempt_total 22949
telemt_upstream_connect_success_total 22304
telemt_upstream_connect_fail_total 645
telemt_upstream_connect_attempts_per_request{bucket="1"} 22949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11583
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 645
telemt_me_keepalive_timeout_total 1796
telemt_me_reconnect_attempts_total 85355
telemt_me_reconnect_success_total 17565
telemt_me_reader_eof_total 20091
telemt_me_idle_close_by_peer_total 20090
telemt_me_route_drop_no_conn_total 440918
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1010826
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2707
telemt_desync_full_logged_total 848
telemt_desync_suppressed_total 1859
telemt_desync_frames_bucket_total{bucket="1_2"} 979
telemt_desync_frames_bucket_total{bucket="3_10"} 949
telemt_desync_frames_bucket_total{bucket="gt_10"} 779
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19842
telemt_me_refill_failed_total 2113
telemt_me_writer_restored_same_endpoint_total 17560
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2277
telemt_user_connections_total{user="hello"} 1010024
telemt_user_connections_current{user="hello"} 670
telemt_user_octets_from_client{user="hello"} 17448669696 (16.25 GB)
telemt_user_octets_to_client{user="hello"} 340437767476 (317.06 GB)
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 92
```