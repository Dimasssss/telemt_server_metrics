# Server Metrics 2026-03-14 04:52:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 168839.0 (46h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4787581
telemt_connections_bad_total 39901
telemt_handshake_timeouts_total 110032
telemt_upstream_connect_attempt_total 35605
telemt_upstream_connect_success_total 35370
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 35605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15956
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_timeout_total 7300
telemt_me_reconnect_attempts_total 34780
telemt_me_reconnect_success_total 24636
telemt_me_reader_eof_total 26440
telemt_me_idle_close_by_peer_total 26439
telemt_me_route_drop_no_conn_total 1813762
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4391916
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16937
telemt_desync_full_logged_total 4577
telemt_desync_suppressed_total 12360
telemt_desync_frames_bucket_total{bucket="1_2"} 4226
telemt_desync_frames_bucket_total{bucket="3_10"} 6469
telemt_desync_frames_bucket_total{bucket="gt_10"} 6242
telemt_pool_swap_total 147
telemt_me_writer_removed_unexpected_total 25302
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 24623
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 666
telemt_user_connections_total{user="hello"} 4393484
telemt_user_connections_current{user="hello"} 922
telemt_user_octets_from_client{user="hello"} 64201004516 (59.79 GB)
telemt_user_octets_to_client{user="hello"} 1384750109161 (1.26 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 68502.8 (19h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 749362
telemt_connections_bad_total 52862
telemt_handshake_timeouts_total 13740
telemt_upstream_connect_attempt_total 18849
telemt_upstream_connect_success_total 18586
telemt_upstream_connect_fail_total 263
telemt_upstream_connect_attempts_per_request{bucket="1"} 18849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8050
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 263
telemt_me_keepalive_timeout_total 2107
telemt_me_reconnect_attempts_total 16581
telemt_me_reconnect_success_total 13127
telemt_me_reader_eof_total 13937
telemt_me_idle_close_by_peer_total 13936
telemt_me_route_drop_no_conn_total 247675
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 595400
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1779
telemt_desync_full_logged_total 524
telemt_desync_suppressed_total 1255
telemt_desync_frames_bucket_total{bucket="1_2"} 373
telemt_desync_frames_bucket_total{bucket="3_10"} 790
telemt_desync_frames_bucket_total{bucket="gt_10"} 616
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 13413
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 13119
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 597351
telemt_user_connections_current{user="hello"} 280
telemt_user_octets_from_client{user="hello"} 6375652585 (5.94 GB)
telemt_user_octets_to_client{user="hello"} 198645502892 (185.00 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 198459.4 (55h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3445777
telemt_connections_bad_total 37127
telemt_handshake_timeouts_total 227836
telemt_upstream_connect_attempt_total 44908
telemt_upstream_connect_success_total 44887
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 44908
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10609
telemt_me_reconnect_attempts_total 39671
telemt_me_reconnect_success_total 34701
telemt_me_reader_eof_total 36864
telemt_me_idle_close_by_peer_total 36863
telemt_me_route_drop_no_conn_total 1178023
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2871039
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9504
telemt_desync_full_logged_total 3194
telemt_desync_suppressed_total 6310
telemt_desync_frames_bucket_total{bucket="1_2"} 1644
telemt_desync_frames_bucket_total{bucket="3_10"} 3442
telemt_desync_frames_bucket_total{bucket="gt_10"} 4418
telemt_pool_swap_total 188
telemt_me_writer_removed_unexpected_total 35182
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 34660
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 481
telemt_user_connections_total{user="hello"} 2870252
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 45831750224 (42.68 GB)
telemt_user_octets_to_client{user="hello"} 1029271961761 (958.58 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 198462.0 (55h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2310642
telemt_connections_bad_total 23085
telemt_handshake_timeouts_total 261283
telemt_upstream_connect_attempt_total 62066
telemt_upstream_connect_success_total 59590
telemt_upstream_connect_fail_total 2339
telemt_upstream_connect_attempts_per_request{bucket="1"} 61792
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35606
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23818
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2338
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20465
telemt_me_reconnect_attempts_total 51732
telemt_me_reconnect_success_total 42692
telemt_me_reader_eof_total 45793
telemt_me_idle_close_by_peer_total 45786
telemt_me_route_drop_no_conn_total 783606
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1832411
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3884
telemt_desync_full_logged_total 1251
telemt_desync_suppressed_total 2633
telemt_desync_frames_bucket_total{bucket="1_2"} 1045
telemt_desync_frames_bucket_total{bucket="3_10"} 1614
telemt_desync_frames_bucket_total{bucket="gt_10"} 1225
telemt_pool_swap_total 176
telemt_me_writer_removed_unexpected_total 43343
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 42668
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 651
telemt_user_connections_total{user="hello"} 1838372
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 27827376447 (25.92 GB)
telemt_user_octets_to_client{user="hello"} 674914620154 (628.56 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 67895.7 (18h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 737898
telemt_connections_bad_total 7979
telemt_handshake_timeouts_total 8894
telemt_upstream_connect_attempt_total 17532
telemt_upstream_connect_success_total 17067
telemt_upstream_connect_fail_total 464
telemt_upstream_connect_attempts_per_request{bucket="1"} 17531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8063
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8978
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 464
telemt_me_keepalive_timeout_total 1537
telemt_me_reconnect_attempts_total 52433
telemt_me_reconnect_success_total 13671
telemt_me_reader_eof_total 15230
telemt_me_idle_close_by_peer_total 15229
telemt_me_route_drop_no_conn_total 281693
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 688586
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1739
telemt_desync_full_logged_total 550
telemt_desync_suppressed_total 1189
telemt_desync_frames_bucket_total{bucket="1_2"} 514
telemt_desync_frames_bucket_total{bucket="3_10"} 681
telemt_desync_frames_bucket_total{bucket="gt_10"} 544
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 15000
telemt_me_refill_failed_total 1207
telemt_me_writer_restored_same_endpoint_total 13666
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1329
telemt_user_connections_total{user="hello"} 688453
telemt_user_connections_current{user="hello"} 370
telemt_user_octets_from_client{user="hello"} 12452492784 (11.60 GB)
telemt_user_octets_to_client{user="hello"} 222669484240 (207.38 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 43
```