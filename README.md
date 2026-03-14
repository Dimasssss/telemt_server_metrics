# Server Metrics 2026-03-14 13:03:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 198314.4 (55h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5773561
telemt_connections_bad_total 67119
telemt_handshake_timeouts_total 127460
telemt_upstream_connect_attempt_total 41553
telemt_upstream_connect_success_total 41285
telemt_upstream_connect_fail_total 268
telemt_upstream_connect_attempts_per_request{bucket="1"} 41553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18757
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 268
telemt_me_keepalive_timeout_total 7871
telemt_me_reconnect_attempts_total 49352
telemt_me_reconnect_success_total 29070
telemt_me_reader_eof_total 31377
telemt_me_idle_close_by_peer_total 31376
telemt_me_route_drop_no_conn_total 2189326
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5292387
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 20435
telemt_desync_full_logged_total 5602
telemt_desync_suppressed_total 14833
telemt_desync_frames_bucket_total{bucket="1_2"} 4910
telemt_desync_frames_bucket_total{bucket="3_10"} 7766
telemt_desync_frames_bucket_total{bucket="gt_10"} 7759
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 30127
telemt_me_refill_failed_total 628
telemt_me_writer_restored_same_endpoint_total 29057
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 1057
telemt_user_connections_total{user="hello"} 5294022
telemt_user_connections_current{user="hello"} 1900
telemt_user_octets_from_client{user="hello"} 82639346912 (76.96 GB)
telemt_user_octets_to_client{user="hello"} 1687615386321 (1.53 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 499
telemt_user_unique_ips_recent_window{user="hello"} 258
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 97978.2 (27h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1136008
telemt_connections_bad_total 59464
telemt_handshake_timeouts_total 27534
telemt_upstream_connect_attempt_total 24775
telemt_upstream_connect_success_total 24467
telemt_upstream_connect_fail_total 308
telemt_upstream_connect_attempts_per_request{bucket="1"} 24775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10827
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 265
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 308
telemt_me_keepalive_timeout_total 2437
telemt_me_reconnect_attempts_total 39352
telemt_me_reconnect_success_total 17566
telemt_me_reader_eof_total 19139
telemt_me_idle_close_by_peer_total 19138
telemt_me_route_drop_no_conn_total 384552
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 936721
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2611
telemt_desync_full_logged_total 823
telemt_desync_suppressed_total 1788
telemt_desync_frames_bucket_total{bucket="1_2"} 679
telemt_desync_frames_bucket_total{bucket="3_10"} 1092
telemt_desync_frames_bucket_total{bucket="gt_10"} 840
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18495
telemt_me_refill_failed_total 674
telemt_me_writer_restored_same_endpoint_total 17558
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 929
telemt_user_connections_total{user="hello"} 938634
telemt_user_connections_current{user="hello"} 768
telemt_user_octets_from_client{user="hello"} 10358208257 (9.65 GB)
telemt_user_octets_to_client{user="hello"} 335653244556 (312.60 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 227934.9 (63h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4094808
telemt_connections_bad_total 47023
telemt_handshake_timeouts_total 285451
telemt_upstream_connect_attempt_total 51370
telemt_upstream_connect_success_total 51348
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 51370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23978
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 264
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 11355
telemt_me_reconnect_attempts_total 45665
telemt_me_reconnect_success_total 39655
telemt_me_reader_eof_total 42117
telemt_me_idle_close_by_peer_total 42115
telemt_me_route_drop_no_conn_total 1407856
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3424325
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10935
telemt_desync_full_logged_total 3692
telemt_desync_suppressed_total 7243
telemt_desync_frames_bucket_total{bucket="1_2"} 2013
telemt_desync_frames_bucket_total{bucket="3_10"} 3938
telemt_desync_frames_bucket_total{bucket="gt_10"} 4984
telemt_pool_swap_total 210
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 40241
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 39614
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 586
telemt_user_connections_total{user="hello"} 3423465
telemt_user_connections_current{user="hello"} 1024
telemt_user_octets_from_client{user="hello"} 58305210628 (54.30 GB)
telemt_user_octets_to_client{user="hello"} 1220528260857 (1.11 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 227937.4 (63h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2666370
telemt_connections_bad_total 23531
telemt_handshake_timeouts_total 348772
telemt_upstream_connect_attempt_total 70111
telemt_upstream_connect_success_total 67601
telemt_upstream_connect_fail_total 2373
telemt_upstream_connect_attempts_per_request{bucket="1"} 69837
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27243
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2372
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 21011
telemt_me_reconnect_attempts_total 61997
telemt_me_reconnect_success_total 49210
telemt_me_reader_eof_total 52711
telemt_me_idle_close_by_peer_total 52703
telemt_me_route_drop_no_conn_total 883009
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2081068
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4124
telemt_desync_full_logged_total 1356
telemt_desync_suppressed_total 2768
telemt_desync_frames_bucket_total{bucket="1_2"} 1173
telemt_desync_frames_bucket_total{bucket="3_10"} 1688
telemt_desync_frames_bucket_total{bucket="gt_10"} 1263
telemt_pool_swap_total 195
telemt_me_writer_removed_unexpected_total 50040
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 49185
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 830
telemt_user_connections_total{user="hello"} 2087656
telemt_user_connections_current{user="hello"} 404
telemt_user_octets_from_client{user="hello"} 30839275191 (28.72 GB)
telemt_user_octets_to_client{user="hello"} 740961730534 (690.07 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 97371.1 (27h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1121435
telemt_connections_bad_total 18178
telemt_handshake_timeouts_total 14284
telemt_upstream_connect_attempt_total 23179
telemt_upstream_connect_success_total 22503
telemt_upstream_connect_fail_total 676
telemt_upstream_connect_attempts_per_request{bucket="1"} 23179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11679
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 676
telemt_me_keepalive_timeout_total 1820
telemt_me_reconnect_attempts_total 88499
telemt_me_reconnect_success_total 17637
telemt_me_reader_eof_total 20259
telemt_me_idle_close_by_peer_total 20258
telemt_me_route_drop_no_conn_total 451564
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1039146
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2751
telemt_desync_full_logged_total 866
telemt_desync_suppressed_total 1885
telemt_desync_frames_bucket_total{bucket="1_2"} 999
telemt_desync_frames_bucket_total{bucket="3_10"} 963
telemt_desync_frames_bucket_total{bucket="gt_10"} 789
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 20010
telemt_me_refill_failed_total 2209
telemt_me_writer_restored_same_endpoint_total 17632
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2373
telemt_user_connections_total{user="hello"} 1038337
telemt_user_connections_current{user="hello"} 741
telemt_user_octets_from_client{user="hello"} 18140784932 (16.89 GB)
telemt_user_octets_to_client{user="hello"} 351601356952 (327.45 GB)
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 94
```