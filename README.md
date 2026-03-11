# Server Metrics 2026-03-11 09:19:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 67956.1 (18h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1441351
telemt_connections_bad_total 18394
telemt_handshake_timeouts_total 40487
telemt_upstream_connect_attempt_total 14185
telemt_upstream_connect_success_total 14176
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 14185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6940
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 776
telemt_me_reconnect_attempts_total 22427
telemt_me_reconnect_success_total 10740
telemt_me_reader_eof_total 11637
telemt_me_idle_close_by_peer_total 11637
telemt_me_route_drop_no_conn_total 529378
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1307161
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6393
telemt_desync_full_logged_total 1770
telemt_desync_suppressed_total 4623
telemt_desync_frames_bucket_total{bucket="1_2"} 1682
telemt_desync_frames_bucket_total{bucket="3_10"} 2429
telemt_desync_frames_bucket_total{bucket="gt_10"} 2282
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 11207
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 10734
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 467
telemt_user_connections_total{user="hello"} 1306828
telemt_user_connections_current{user="hello"} 1311
telemt_user_octets_from_client{user="hello"} 17259430116 (16.07 GB)
telemt_user_octets_to_client{user="hello"} 375109541320 (349.35 GB)
telemt_user_unique_ips_current{user="hello"} 346
telemt_user_unique_ips_recent_window{user="hello"} 186
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 68012.9 (18h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 554663
telemt_connections_bad_total 9343
telemt_handshake_timeouts_total 30617
telemt_upstream_connect_attempt_total 23107
telemt_upstream_connect_success_total 20180
telemt_upstream_connect_fail_total 2927
telemt_upstream_connect_attempts_per_request{bucket="1"} 23107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8759
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2927
telemt_me_keepalive_timeout_total 2097
telemt_me_reconnect_attempts_total 14664
telemt_me_reconnect_success_total 13828
telemt_me_reader_eof_total 14639
telemt_me_idle_close_by_peer_total 14637
telemt_me_route_drop_no_conn_total 232199
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 470092
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2190
telemt_desync_full_logged_total 675
telemt_desync_suppressed_total 1515
telemt_desync_frames_bucket_total{bucket="1_2"} 729
telemt_desync_frames_bucket_total{bucket="3_10"} 788
telemt_desync_frames_bucket_total{bucket="gt_10"} 673
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 13990
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 13806
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 472329
telemt_user_connections_current{user="hello"} 476
telemt_user_octets_from_client{user="hello"} 4615544786 (4.30 GB)
telemt_user_octets_to_client{user="hello"} 126623118928 (117.93 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 68012.7 (18h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 966454
telemt_connections_bad_total 7443
telemt_handshake_timeouts_total 94918
telemt_upstream_connect_attempt_total 18424
telemt_upstream_connect_success_total 18198
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 18424
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8178
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_keepalive_timeout_total 767
telemt_me_reconnect_attempts_total 26081
telemt_me_reconnect_success_total 13717
telemt_me_reader_eof_total 14736
telemt_me_idle_close_by_peer_total 14736
telemt_me_route_drop_no_conn_total 317056
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 826041
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2367
telemt_desync_full_logged_total 701
telemt_desync_suppressed_total 1666
telemt_desync_frames_bucket_total{bucket="1_2"} 572
telemt_desync_frames_bucket_total{bucket="3_10"} 861
telemt_desync_frames_bucket_total{bucket="gt_10"} 934
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 14281
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 13706
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 564
telemt_user_connections_total{user="hello"} 826920
telemt_user_connections_current{user="hello"} 735
telemt_user_octets_from_client{user="hello"} 9823807561 (9.15 GB)
telemt_user_octets_to_client{user="hello"} 250807141541 (233.58 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 68013.0 (18h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 705748
telemt_connections_bad_total 63820
telemt_handshake_timeouts_total 68545
telemt_upstream_connect_attempt_total 18783
telemt_upstream_connect_success_total 18783
telemt_upstream_connect_attempts_per_request{bucket="1"} 18783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8339
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 707
telemt_me_reconnect_attempts_total 16438
telemt_me_reconnect_success_total 15384
telemt_me_reader_eof_total 16337
telemt_me_idle_close_by_peer_total 16336
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 220711
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 551655
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1245
telemt_desync_full_logged_total 471
telemt_desync_suppressed_total 774
telemt_desync_frames_bucket_total{bucket="1_2"} 417
telemt_desync_frames_bucket_total{bucket="3_10"} 470
telemt_desync_frames_bucket_total{bucket="gt_10"} 358
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 15564
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 15361
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 551029
telemt_user_connections_current{user="hello"} 466
telemt_user_octets_from_client{user="hello"} 6465072224 (6.02 GB)
telemt_user_octets_to_client{user="hello"} 155803189756 (145.10 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 68012.8 (18h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 747481
telemt_connections_bad_total 5983
telemt_handshake_timeouts_total 7027
telemt_upstream_connect_attempt_total 18505
telemt_upstream_connect_success_total 18431
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 18505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8783
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 766
telemt_me_reconnect_attempts_total 18707
telemt_me_reconnect_success_total 14915
telemt_me_reader_eof_total 15771
telemt_me_idle_close_by_peer_total 15771
telemt_me_route_drop_no_conn_total 255304
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 677027
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2911
telemt_desync_full_logged_total 1103
telemt_desync_suppressed_total 1808
telemt_desync_frames_bucket_total{bucket="1_2"} 1019
telemt_desync_frames_bucket_total{bucket="3_10"} 1197
telemt_desync_frames_bucket_total{bucket="gt_10"} 695
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 15223
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 14915
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 308
telemt_user_connections_total{user="hello"} 676711
telemt_user_connections_current{user="hello"} 718
telemt_user_octets_from_client{user="hello"} 10811392099 (10.07 GB)
telemt_user_octets_to_client{user="hello"} 242953858894 (226.27 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 94
```