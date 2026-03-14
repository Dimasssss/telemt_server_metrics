# Server Metrics 2026-03-14 13:14:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 198928.9 (55h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5796665
telemt_connections_bad_total 67984
telemt_handshake_timeouts_total 127967
telemt_upstream_connect_attempt_total 41593
telemt_upstream_connect_success_total 41325
telemt_upstream_connect_fail_total 268
telemt_upstream_connect_attempts_per_request{bucket="1"} 41593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18788
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 268
telemt_me_keepalive_timeout_total 7910
telemt_me_reconnect_attempts_total 49386
telemt_me_reconnect_success_total 29104
telemt_me_reader_eof_total 31411
telemt_me_idle_close_by_peer_total 31410
telemt_me_route_drop_no_conn_total 2199376
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5312942
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 20541
telemt_desync_full_logged_total 5633
telemt_desync_suppressed_total 14908
telemt_desync_frames_bucket_total{bucket="1_2"} 4934
telemt_desync_frames_bucket_total{bucket="3_10"} 7800
telemt_desync_frames_bucket_total{bucket="gt_10"} 7807
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 30161
telemt_me_refill_failed_total 628
telemt_me_writer_restored_same_endpoint_total 29091
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 1057
telemt_user_connections_total{user="hello"} 5314595
telemt_user_connections_current{user="hello"} 1784
telemt_user_octets_from_client{user="hello"} 82932504028 (77.24 GB)
telemt_user_octets_to_client{user="hello"} 1695695052481 (1.54 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 479
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 98592.6 (27h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1146308
telemt_connections_bad_total 60211
telemt_handshake_timeouts_total 27776
telemt_upstream_connect_attempt_total 30140
telemt_upstream_connect_success_total 29821
telemt_upstream_connect_fail_total 319
telemt_upstream_connect_attempts_per_request{bucket="1"} 30140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18387
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11083
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 297
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 319
telemt_me_keepalive_timeout_total 2451
telemt_me_reconnect_attempts_total 40743
telemt_me_reconnect_success_total 17581
telemt_me_reader_eof_total 19197
telemt_me_idle_close_by_peer_total 19196
telemt_me_route_drop_no_conn_total 386669
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 940274
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2614
telemt_desync_full_logged_total 825
telemt_desync_suppressed_total 1789
telemt_desync_frames_bucket_total{bucket="1_2"} 681
telemt_desync_frames_bucket_total{bucket="3_10"} 1093
telemt_desync_frames_bucket_total{bucket="gt_10"} 840
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18553
telemt_me_refill_failed_total 717
telemt_me_writer_restored_same_endpoint_total 17573
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 972
telemt_user_connections_total{user="hello"} 947481
telemt_user_connections_current{user="hello"} 563
telemt_user_octets_from_client{user="hello"} 10557479063 (9.83 GB)
telemt_user_octets_to_client{user="hello"} 339755553438 (316.42 GB)
telemt_user_msgs_from_client{user="hello"} 104528
telemt_user_msgs_to_client{user="hello"} 196947
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 228549.3 (63h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4113582
telemt_connections_bad_total 49645
telemt_handshake_timeouts_total 286656
telemt_upstream_connect_attempt_total 51419
telemt_upstream_connect_success_total 51397
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 51419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24004
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 264
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 11374
telemt_me_reconnect_attempts_total 45714
telemt_me_reconnect_success_total 39704
telemt_me_reader_eof_total 42168
telemt_me_idle_close_by_peer_total 42166
telemt_me_route_drop_no_conn_total 1414381
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3438456
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11005
telemt_desync_full_logged_total 3707
telemt_desync_suppressed_total 7298
telemt_desync_frames_bucket_total{bucket="1_2"} 2024
telemt_desync_frames_bucket_total{bucket="3_10"} 3964
telemt_desync_frames_bucket_total{bucket="gt_10"} 5017
telemt_pool_swap_total 210
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 40292
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 39663
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 588
telemt_user_connections_total{user="hello"} 3437589
telemt_user_connections_current{user="hello"} 1024
telemt_user_octets_from_client{user="hello"} 58473362316 (54.46 GB)
telemt_user_octets_to_client{user="hello"} 1226808149609 (1.12 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 228551.8 (63h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2677332
telemt_connections_bad_total 23533
telemt_handshake_timeouts_total 352585
telemt_upstream_connect_attempt_total 70250
telemt_upstream_connect_success_total 67740
telemt_upstream_connect_fail_total 2373
telemt_upstream_connect_attempts_per_request{bucket="1"} 69976
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40256
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27318
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2372
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 21023
telemt_me_reconnect_attempts_total 62136
telemt_me_reconnect_success_total 49348
telemt_me_reader_eof_total 52849
telemt_me_idle_close_by_peer_total 52841
telemt_me_route_drop_no_conn_total 885037
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2087560
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
telemt_me_writer_removed_unexpected_total 50178
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 49323
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 830
telemt_user_connections_total{user="hello"} 2094200
telemt_user_connections_current{user="hello"} 530
telemt_user_octets_from_client{user="hello"} 30882732843 (28.76 GB)
telemt_user_octets_to_client{user="hello"} 743453104046 (692.39 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 97985.4 (27h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1129790
telemt_connections_bad_total 18384
telemt_handshake_timeouts_total 14339
telemt_upstream_connect_attempt_total 23206
telemt_upstream_connect_success_total 22530
telemt_upstream_connect_fail_total 676
telemt_upstream_connect_attempts_per_request{bucket="1"} 23206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11699
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 676
telemt_me_keepalive_timeout_total 1833
telemt_me_reconnect_attempts_total 89576
telemt_me_reconnect_success_total 17658
telemt_me_reader_eof_total 20313
telemt_me_idle_close_by_peer_total 20312
telemt_me_route_drop_no_conn_total 455117
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1046794
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2765
telemt_desync_full_logged_total 876
telemt_desync_suppressed_total 1889
telemt_desync_frames_bucket_total{bucket="1_2"} 1006
telemt_desync_frames_bucket_total{bucket="3_10"} 969
telemt_desync_frames_bucket_total{bucket="gt_10"} 790
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 20064
telemt_me_refill_failed_total 2242
telemt_me_writer_restored_same_endpoint_total 17653
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2406
telemt_user_connections_total{user="hello"} 1045999
telemt_user_connections_current{user="hello"} 693
telemt_user_octets_from_client{user="hello"} 18258484660 (17.00 GB)
telemt_user_octets_to_client{user="hello"} 355329543360 (330.93 GB)
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 92
```