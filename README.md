# Server Metrics 2026-03-14 05:43:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 171906.4 (47h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4853142
telemt_connections_bad_total 40022
telemt_handshake_timeouts_total 112296
telemt_upstream_connect_attempt_total 36145
telemt_upstream_connect_success_total 35909
telemt_upstream_connect_fail_total 236
telemt_upstream_connect_attempts_per_request{bucket="1"} 36145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16226
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 236
telemt_me_keepalive_timeout_total 7306
telemt_me_reconnect_attempts_total 35188
telemt_me_reconnect_success_total 25042
telemt_me_reader_eof_total 26878
telemt_me_idle_close_by_peer_total 26877
telemt_me_route_drop_no_conn_total 1837364
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4452197
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17125
telemt_desync_full_logged_total 4620
telemt_desync_suppressed_total 12505
telemt_desync_frames_bucket_total{bucket="1_2"} 4273
telemt_desync_frames_bucket_total{bucket="3_10"} 6548
telemt_desync_frames_bucket_total{bucket="gt_10"} 6304
telemt_pool_swap_total 150
telemt_me_writer_removed_unexpected_total 25718
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 25029
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 676
telemt_user_connections_total{user="hello"} 4453738
telemt_user_connections_current{user="hello"} 1054
telemt_user_octets_from_client{user="hello"} 65091268056 (60.62 GB)
telemt_user_octets_to_client{user="hello"} 1406158843449 (1.28 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 348
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 71570.2 (19h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 781181
telemt_connections_bad_total 53075
telemt_handshake_timeouts_total 14442
telemt_upstream_connect_attempt_total 19615
telemt_upstream_connect_success_total 19347
telemt_upstream_connect_fail_total 268
telemt_upstream_connect_attempts_per_request{bucket="1"} 19615
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8429
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 268
telemt_me_keepalive_timeout_total 2115
telemt_me_reconnect_attempts_total 17209
telemt_me_reconnect_success_total 13750
telemt_me_reader_eof_total 14615
telemt_me_idle_close_by_peer_total 14614
telemt_me_route_drop_no_conn_total 254802
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 616176
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1837
telemt_desync_full_logged_total 549
telemt_desync_suppressed_total 1288
telemt_desync_frames_bucket_total{bucket="1_2"} 384
telemt_desync_frames_bucket_total{bucket="3_10"} 821
telemt_desync_frames_bucket_total{bucket="gt_10"} 632
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 14047
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 13742
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 297
telemt_user_connections_total{user="hello"} 618128
telemt_user_connections_current{user="hello"} 430
telemt_user_octets_from_client{user="hello"} 6582526981 (6.13 GB)
telemt_user_octets_to_client{user="hello"} 208989797460 (194.64 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 201527.1 (55h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3486263
telemt_connections_bad_total 38115
telemt_handshake_timeouts_total 230554
telemt_upstream_connect_attempt_total 45550
telemt_upstream_connect_success_total 45529
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 45550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23972
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21310
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10631
telemt_me_reconnect_attempts_total 40183
telemt_me_reconnect_success_total 35212
telemt_me_reader_eof_total 37408
telemt_me_idle_close_by_peer_total 37407
telemt_me_route_drop_no_conn_total 1192239
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2905105
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9588
telemt_desync_full_logged_total 3225
telemt_desync_suppressed_total 6363
telemt_desync_frames_bucket_total{bucket="1_2"} 1666
telemt_desync_frames_bucket_total{bucket="3_10"} 3469
telemt_desync_frames_bucket_total{bucket="gt_10"} 4453
telemt_pool_swap_total 191
telemt_me_writer_removed_unexpected_total 35700
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 35171
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 488
telemt_user_connections_total{user="hello"} 2904316
telemt_user_connections_current{user="hello"} 498
telemt_user_octets_from_client{user="hello"} 46810421956 (43.60 GB)
telemt_user_octets_to_client{user="hello"} 1040030877085 (968.60 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 201529.6 (55h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2334177
telemt_connections_bad_total 23144
telemt_handshake_timeouts_total 268688
telemt_upstream_connect_attempt_total 62924
telemt_upstream_connect_success_total 60442
telemt_upstream_connect_fail_total 2345
telemt_upstream_connect_attempts_per_request{bucket="1"} 62650
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24171
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2344
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20479
telemt_me_reconnect_attempts_total 52453
telemt_me_reconnect_success_total 43411
telemt_me_reader_eof_total 46548
telemt_me_idle_close_by_peer_total 46541
telemt_me_route_drop_no_conn_total 789653
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1847351
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3887
telemt_desync_full_logged_total 1254
telemt_desync_suppressed_total 2633
telemt_desync_frames_bucket_total{bucket="1_2"} 1045
telemt_desync_frames_bucket_total{bucket="3_10"} 1616
telemt_desync_frames_bucket_total{bucket="gt_10"} 1226
telemt_pool_swap_total 178
telemt_me_writer_removed_unexpected_total 44071
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 43387
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 660
telemt_user_connections_total{user="hello"} 1853347
telemt_user_connections_current{user="hello"} 305
telemt_user_octets_from_client{user="hello"} 28085176371 (26.16 GB)
telemt_user_octets_to_client{user="hello"} 681152319566 (634.37 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 70963.1 (19h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 758551
telemt_connections_bad_total 8029
telemt_handshake_timeouts_total 8995
telemt_upstream_connect_attempt_total 18361
telemt_upstream_connect_success_total 17879
telemt_upstream_connect_fail_total 482
telemt_upstream_connect_attempts_per_request{bucket="1"} 18361
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9397
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 482
telemt_me_keepalive_timeout_total 1559
telemt_me_reconnect_attempts_total 55525
telemt_me_reconnect_success_total 14348
telemt_me_reader_eof_total 15990
telemt_me_idle_close_by_peer_total 15989
telemt_me_route_drop_no_conn_total 290886
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 708329
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1755
telemt_desync_full_logged_total 559
telemt_desync_suppressed_total 1196
telemt_desync_frames_bucket_total{bucket="1_2"} 519
telemt_desync_frames_bucket_total{bucket="3_10"} 688
telemt_desync_frames_bucket_total{bucket="gt_10"} 548
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 15760
telemt_me_refill_failed_total 1282
telemt_me_writer_restored_same_endpoint_total 14343
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1412
telemt_user_connections_total{user="hello"} 708195
telemt_user_connections_current{user="hello"} 515
telemt_user_octets_from_client{user="hello"} 12693049024 (11.82 GB)
telemt_user_octets_to_client{user="hello"} 236260135656 (220.03 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 57
```