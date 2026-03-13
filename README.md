# Server Metrics 2026-03-13 18:24:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 131148.3 (36h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4190680
telemt_connections_bad_total 37533
telemt_handshake_timeouts_total 102245
telemt_upstream_connect_attempt_total 27683
telemt_upstream_connect_success_total 27503
telemt_upstream_connect_fail_total 180
telemt_upstream_connect_attempts_per_request{bucket="1"} 27683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12162
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 180
telemt_me_keepalive_timeout_total 5783
telemt_me_reconnect_attempts_total 28730
telemt_me_reconnect_success_total 18623
telemt_me_reader_eof_total 19997
telemt_me_idle_close_by_peer_total 19996
telemt_me_route_drop_no_conn_total 1567692
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3829810
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14955
telemt_desync_full_logged_total 3979
telemt_desync_suppressed_total 10976
telemt_desync_frames_bucket_total{bucket="1_2"} 3704
telemt_desync_frames_bucket_total{bucket="3_10"} 5693
telemt_desync_frames_bucket_total{bucket="gt_10"} 5558
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 19203
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 18610
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 580
telemt_user_connections_total{user="hello"} 3831981
telemt_user_connections_current{user="hello"} 1664
telemt_user_octets_from_client{user="hello"} 53696723892 (50.01 GB)
telemt_user_octets_to_client{user="hello"} 1196462254761 (1.09 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 444
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 30811.9 (8h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 457258
telemt_connections_bad_total 35524
telemt_handshake_timeouts_total 10689
telemt_upstream_connect_attempt_total 8740
telemt_upstream_connect_success_total 8558
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 8740
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4900
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3495
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1609
telemt_me_reconnect_attempts_total 8954
telemt_me_reconnect_success_total 5553
telemt_me_reader_eof_total 5870
telemt_me_idle_close_by_peer_total 5869
telemt_me_route_drop_no_conn_total 172184
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 397927
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1392
telemt_desync_full_logged_total 365
telemt_desync_suppressed_total 1027
telemt_desync_frames_bucket_total{bucket="1_2"} 274
telemt_desync_frames_bucket_total{bucket="3_10"} 642
telemt_desync_frames_bucket_total{bucket="gt_10"} 476
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5736
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 5545
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 399264
telemt_user_connections_current{user="hello"} 526
telemt_user_octets_from_client{user="hello"} 4122150431 (3.84 GB)
telemt_user_octets_to_client{user="hello"} 123390874376 (114.92 GB)
telemt_user_msgs_from_client{user="hello"} 4402
telemt_user_msgs_to_client{user="hello"} 9145
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 160768.6 (44h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3063230
telemt_connections_bad_total 28913
telemt_handshake_timeouts_total 205271
telemt_upstream_connect_attempt_total 35789
telemt_upstream_connect_success_total 35779
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 35789
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17145
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3513
telemt_me_reconnect_attempts_total 30006
telemt_me_reconnect_success_total 27451
telemt_me_reader_eof_total 29108
telemt_me_idle_close_by_peer_total 29107
telemt_me_route_drop_no_conn_total 1047951
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2534393
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8543
telemt_desync_full_logged_total 2834
telemt_desync_suppressed_total 5709
telemt_desync_frames_bucket_total{bucket="1_2"} 1383
telemt_desync_frames_bucket_total{bucket="3_10"} 3125
telemt_desync_frames_bucket_total{bucket="gt_10"} 4035
telemt_pool_swap_total 151
telemt_me_writer_removed_unexpected_total 27772
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 27410
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 321
telemt_user_connections_total{user="hello"} 2533720
telemt_user_connections_current{user="hello"} 1035
telemt_user_octets_from_client{user="hello"} 41807372552 (38.94 GB)
telemt_user_octets_to_client{user="hello"} 889882388105 (828.77 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 160769.1 (44h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1971803
telemt_connections_bad_total 19947
telemt_handshake_timeouts_total 181217
telemt_upstream_connect_attempt_total 49701
telemt_upstream_connect_success_total 47357
telemt_upstream_connect_fail_total 2207
telemt_upstream_connect_attempts_per_request{bucket="1"} 49427
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18969
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2206
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11973
telemt_me_reconnect_attempts_total 42490
telemt_me_reconnect_success_total 33504
telemt_me_reader_eof_total 35977
telemt_me_idle_close_by_peer_total 35970
telemt_me_route_drop_no_conn_total 701833
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1627580
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3278
telemt_desync_full_logged_total 1066
telemt_desync_suppressed_total 2212
telemt_desync_frames_bucket_total{bucket="1_2"} 900
telemt_desync_frames_bucket_total{bucket="3_10"} 1337
telemt_desync_frames_bucket_total{bucket="gt_10"} 1041
telemt_pool_swap_total 140
telemt_me_writer_removed_unexpected_total 34056
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 33480
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 552
telemt_user_connections_total{user="hello"} 1632275
telemt_user_connections_current{user="hello"} 650
telemt_user_octets_from_client{user="hello"} 25120658765 (23.40 GB)
telemt_user_octets_to_client{user="hello"} 614660114646 (572.45 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 30204.8 (8h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 494615
telemt_connections_bad_total 4704
telemt_handshake_timeouts_total 5086
telemt_upstream_connect_attempt_total 6734
telemt_upstream_connect_success_total 6515
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 6734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3446
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_keepalive_timeout_total 877
telemt_me_reconnect_attempts_total 21847
telemt_me_reconnect_success_total 4983
telemt_me_reader_eof_total 5606
telemt_me_idle_close_by_peer_total 5606
telemt_me_route_drop_no_conn_total 188770
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 463014
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1350
telemt_desync_full_logged_total 431
telemt_desync_suppressed_total 919
telemt_desync_frames_bucket_total{bucket="1_2"} 426
telemt_desync_frames_bucket_total{bucket="3_10"} 532
telemt_desync_frames_bucket_total{bucket="gt_10"} 392
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5550
telemt_me_refill_failed_total 525
telemt_me_writer_restored_same_endpoint_total 4979
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 567
telemt_user_connections_total{user="hello"} 462984
telemt_user_connections_current{user="hello"} 755
telemt_user_octets_from_client{user="hello"} 5192331232 (4.84 GB)
telemt_user_octets_to_client{user="hello"} 147951504532 (137.79 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 90
```